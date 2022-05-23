Cation-Ordering-ML

Datasets utilized to construct all models as mentioned in the manuscript can be found under the folder 'Datasets' in this repository. The naming conventions of Dataset are given below:


Datasets for the classification of three types of cation ordering (Columnar, Layer, rocksalt):

1. Model_I.csv 

2. Model_II.csv 

3. Model_III.csv 


1. Model_I.csv:

	(i) Model_I.csv file is built by geometry deriven features of AA'BB'O6 compounds retrieved from First principle computations.
 
	(ii) Total number of data points = 399

	(iii) Total number of Columns = 68 (include Compound name & target_label)

	(iv) Target(end point) = target_label [ C- 0, L- 1, R- 2]

	(v) Total number of features = 16

	(vi) Total number of entries in columnar = 135

	(vii) Total number of entries in layer = 132

	(viii) Total number of entries in rocksalt = 132

Features explanation for Model_I.csv :

	a. Charge state (C_A – charge state of A-site, C_A' – charge state of A’ site, C_B- charge state of B-site, C_B’- charge state of B’-site )

	b. Co-ordination number(Cn_A – Co-ordination number of A-site, Cn_A’ – Co-ordination number of A’-site, Cn_B– Co-ordination number of B-site, Cn_B’ – Co-ordination number of B’-site)

	c. Ionic radius (r_Asite – Ionic radius of A-site, r_A’site – Ionic radius of A’-site, r_Bsite – Ionic radius of B-site, r_B’site – Ionic radius of B’-site, Avg_AA‘ – Average ionic radius of AA’, Avg_BB' – Average ionic radius of BB’ 

	d. Tolerance factor (TF – Tolerance factor of AA’BB’O6)

	e. Optimized Energy (Energy – optimized energy of AA’BB’O6)

	f. Fermi energy (Fermi_energy – Fermi energy of AA’BB’O6)

	g. Cell parameter (_cell_length_a,  _cell_length_b , _cell_length_c – cell length of a,b,c)

	h. Cell angle (a,b,g) (_cell_angle_alpha, _cell_angle_beta , _cell_angle_gamma)

	i. Cell Volume (_cell_volume )

	j. Space group (LS, HS) (LS space_group_, HS Space_group_) – space group and space group number of low symmetry and high symmetry)

	k. Space group number (LS Space_group_No_, HS Space_group_No_ - Space group number of low and high symmetry)

	l. Total magnetic moment (Total_mag_)

	m. Individual magnetic moment (mag_B, mag_B‘, mag_O – individual magnetic moment of B,B’ and O-site)

	n. S,p,d occupancies (A_s, A_p, A_d- s,p,d occupancy of A-site, A'_s, A'_p, A'_d - s,p,d occupancy of A’-site, B_s, B_p   ,B_d - s,p,d occupancy of B-site, B'_s, B'_p , B'_d - s,p,d occupancy of B’-site)

	o. Antiferroelectric Displacement (|A_dis|, |A'_dis| - antiferroelectric displacement of A,A’-site)

	p. Tilt & Rotation angle (tilt_angle, rot_angle )

2. Model_II.csv	

	(i) Model_II.csv file is constructed amplitudes of structural modes.

	(ii) Total number of data points = 194

	(iii) Total number of Columns = 9 (include Compound name & target_label)

	(iv) Target(end point) = target_label [ C- 0, L- 1, R- 2]

	(v) Total number of features = 7

	(vi) Total number of entries in columnar = 75

	(vii) Total number of entries in layer = 50

	(viii) Total number of entries in rocksalt = 69

Features explanation:

	a. Q_R- - Out-of-phase rotation

	b. Q_R+ - In-phase rotation

	c. Q_T -Tilt

	d. Q_AFE_(A) - Antiferroelectic A-site displacement

	e. Q_AFE_(O) - Antiferroelectric O-site displacement

	f. CD_(2D) - 2D Charge Disproportionation

	g. CD_(3D) - 3D Charge Disproportionation

3. Model_III.csv:

	(i) Model_III.csv file is combined with both geometry driven and structural driven features.

	(ii) Total number of data points = 158

	(iii) Total number of Columns = 75 (include Compound name & target_label)

	(iv) Target(end point) = target_label [ C- 0, L- 1, R- 2]

	(v) Total number of features = 23

	(vi) Total number of entries in columnar = 63

	(vii) Total number of entries in layer = 43

	(viii) Total number of entries in rocksalt = 52

Features explanation:

	a. Charge state (C_A – charge state of A-site, C_A' – charge state of A’ site, C_B- charge state of B-site, C_B’- charge state of B’-site )

	b. Co-ordination number(Cn_A – Co-ordination number of A-site, Cn_A’ – Co-ordination number of A’-site, Cn_B– Co-ordination number of B-site, Cn_B’ – Co-ordination number of B’-site)

	c. Ionic radius (r_Asite – Ionic radius of A-site, r_A’site – Ionic radius of A’-site, r_Bsite – Ionic radius of B-site, r_B’site – Ionic radius of B’-site, Avg_AA‘ – Average ionic radius of AA’, Avg_BB‘ – Average ionic radius of BB’ 

	d. Tolerance factor (TF – Tolerance factor of AA’BB’O6)

	e. Optimized Energy (Energy – optimized energy of AA’BB’O6)

	f. Fermi energy (Fermi_energy – Fermi energy of AA’BB’O6)

	g. Cell parameter (_cell_length_a,  _cell_length_b , _cell_length_c – cell length of a,b,c)

	h. Cell angle (a,b,g) (_cell_angle_alpha, _cell_angle_beta , _cell_angle_gamma)

	i. Cell Volume (_cell_volume )

	j. Space group (LS, HS) (LS space_group_, HS Space_group_) – space group and space group number of low symmetry and high symmetry)

	k. Space group number (LS Space_group_No_, HS Space_group_No_ - Space group number of low and high symmetry)

	l. Total magnetic moment (Total_mag_)

	m. Individual magnetic moment (mag_B, mag_B', mag_O – individual magnetic moment of B, B’ and O-site)

	n. S,p,d occupancies (A_s, A_p, A_d- s,p,d occupancy of A-site, A'_s, A'_p, A'_d - s,p,d occupancy of A’-site, B_s, B_p   ,B_d - s,p,d occupancy of B-site, B'_s, B'_p , B'_d - s,p,d occupancy of B’-site)

	o. Antiferroelectric Displacement (|A_dis|, |A'_dis| - antiferroelectric displacement of A,A’-site)

	p. Tilt & Rotation angle (tilt_angle, rot_angle )

	q. Q_R- - Out-of-phase rotation

	r. Q_R+ - In-phase rotation

	s. Q_T -Tilt

	t. Q_AFE_(A) - Antiferroelectic A-site displacement

	u. Q_AFE_(O) - Antiferroelectric O-site displacement

	v. CD_(2D) - 2D Charge Disproportionation

	w. CD_(3D) - 3D Charge Disproportionation	


Dataset for the classification of clear layered ordering:

1. Model_IV.csv 

2. Model_V_VI_VII.csv 


1. Model_IV.csv:
 
	(i) Model_IV.csv file contains geometry driven features of AA'BB'O6 layered compounds retrieved from First principle computations.

	(ii) Total number of data points = 108

	(iii) Total number of Columns = 73 (include Compound name & target_label)
	
	(iv) Total number of features = 17

Features explanation:

	a. Charge state (C_A – charge state of A-site, C_A' – charge state of A’ site, C_B- charge state of B-site, C_B’- charge state of B’-site )

	b. Co-ordination number(Cn_A – Co-ordination number of A-site, Cn_A’ – Co-ordination number of A’-site, Cn_B– Co-ordination number of B-site, Cn_B’ – Co-ordination number of B’-site)

	c. Ionic radius (r_Asite – Ionic radius of A-site, r_A’site – Ionic radius of A’-site, r_Bsite – Ionic radius of B-site, r_B’site – Ionic radius of B’-site, Avg_AA‘ – Average ionic radius of AA’, Avg_BB‘ – Average ionic radius of BB’ 

	d. Tolerance factor (TF – Tolerance factor of AA’BB’O6)

	e. Optimized Energy (Energy – optimized energy of AA’BB’O6)

	f. Fermi energy (Fermi_energy – Fermi energy of AA’BB’O6)

	g. Cell parameter (_cell_length_a,  _cell_length_b , _cell_length_c – cell length of a,b,c)

	h. Cell angle (a,b,g) (_cell_angle_alpha, _cell_angle_beta , _cell_angle_gamma)

	i. Cell Volume (_cell_volume )

	j. Space group (LS, HS) (LS space_group_, HS Space_group_) – space group and space group number of low symmetry and high symmetry)

	k. Space group number (LS Space_group_No_, HS Space_group_No_ - Space group number of low and high symmetry)

	l. Total magnetic moment (Total_mag_)

	m. Individual magnetic moment (mag_B, mag_B', mag_O – individual magnetic moment of B,B’ and O-site)

	n. S,p,d occupancies (A_s, A_p, A_d- s,p,d occupancy of A-site, A'_s, A'_p, A'_d - s,p,d occupancy of A’-site, B_s, B_p   ,B_d - s,p,d occupancy of B-site, B'_s, B'_p , B'_d - s,p,d occupancy of B’-site)

	o. Antiferroelectric Displacement (|A_dis|, |A'_dis| - antiferroelectric displacement of A,A’-site)

	p. Tilt & Rotation angle (tilt_angle, rot_angle )

	q. Energy Difference (Energy_diff(meV), Energy_5-atom_unitcell)

2. Model_V_VI_VII.csv 

	(i) Model_V_VI_VII.csv file has both geometry driven and structural driven features of AA'BB'O6 layered compounds. 

	(ii) Total number of data points = 101

	(iii) Total number of Columns = 78 (include Compound name & target_label)
	
	(iv) Total number of features = 22

Features explanation:

	a. Charge state (C_A – charge state of A-site, C_A' – charge state of A’ site, C_B- charge state of B-site, C_B’- charge state of B’-site )

	b. Co-ordination number(Cn_A – Co-ordination number of A-site, Cn_A’ – Co-ordination number of A’-site, Cn_B– Co-ordination number of B-site, Cn_B’ – Co-ordination number of B’-site)

	c. Ionic radius (r_Asite – Ionic radius of A-site, r_A’site – Ionic radius of A’-site, r_Bsite – Ionic radius of B-site, r_B’site – Ionic radius of B’-site, Avg_AA‘ – Average ionic radius of AA’, Avg_BB‘ – Average ionic radius of BB’ 

	d. Tolerance factor (TF – Tolerance factor of AA’BB’O6)

	e. Optimized Energy (Energy – optimized energy of AA’BB’O6)

	f. Fermi energy (Fermi_energy – Fermi energy of AA’BB’O6)

	g. Cell parameter (_cell_length_a,  _cell_length_b , _cell_length_c – cell length of a,b,c)

	h. Cell angle (a,b,g) (_cell_angle_alpha, _cell_angle_beta , _cell_angle_gamma)

	i. Cell Volume (_cell_volume )

	j. Space group (LS, HS) (LS space_group_, HS Space_group_) – space group and space group number of low symmetry and high symmetry)

	k. Space group number (LS Space_group_No_, HS Space_group_No_ - Space group number of low and high symmetry)

	l. Total magnetic moment (Total_mag_)

	m. Individual magnetic moment (mag_B, mag_B', mag_O – individual magnetic moment of B,B’ and O-site)

	n. S,p,d occupancies (A_s, A_p, A_d- s,p,d occupancy of A-site, A'_s, A'_p, A'_d - s,p,d occupancy of A’-site, B_s, B_p   ,B_d - s,p,d occupancy of B-site, B'_s, B'_p , B'_d - s,p,d occupancy of B’-site)

	o. Antiferroelectric Displacement (|A_dis|, |A'_dis| - antiferroelectric displacement of A,A’-site)

	p. Tilt & Rotation angle (tilt_angle, rot_angle )

	q. Energy Difference (Energy_diff(meV), Energy_5-atom_unitcell)

	r. Q_R+ - In-phase rotation

	s. Q_T -Tilt

	t. Q_AFE_(A) - Antiferroelectic A-site displacement

	u. Q_AFE_(O) - Antiferroelectric O-site displacement

	v. CD_(2D) - 2D Charge Disproportionation

