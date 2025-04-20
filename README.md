# xampp
cp -r /c/xampp/mysql/data /c/xampp/mysql/data_old && rm -r /c/xampp/mysql/data/mysql/ /c/xampp/mysql/data/performance_schema/ /c/xampp/mysql/data/phpmyadmin/ /c/xampp/mysql/data/test/ && find /c/xampp/mysql/backup/ -mindepth 1 -maxdepth 1 ! -name "ibdata1" -exec cp -r {} /c/xampp/mysql/data/ \;
