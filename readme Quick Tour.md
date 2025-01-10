\app\Http\Controllers (these handles the HTTP request and routes them specific outcome)
 AuthController.php
 BarangController.php
 Controller.php
 DashboardController.php
 
\database\migrations (Use to create initail table when you use composer migration)
 2014_10_12_000000_create_users_table.php
 2014_10_12_100000_create_password_reset_tokens_table.php
 2019_08_19_000000_create_failed_jobs_table.php
 2019_12_14_000001_create_personal_access_tokens_table.php
 2023_07_31_144147_create_barangs_table.php
  

these 3 Views handle the Interface  
  
\resources\views\auth (Interface of Login and Register)
 login.blade.php
 register.blade.php
 
 
\resources\views\barang (Interface of Items CRUD)
 barang-add.blade.php
 barang-edit.blade.php
 barang.blade.php


\resources\views\dashboard (Interface of Main Dshboard)
 dashboard.blade.php