Upon upload de img The TMP_name of $FILE returns as null blocking the upload.
The reason behind was the size of file, the default of php.ini is 2mb so is needed to change the code in the php.ini so "upload_max_filesize = 2M" becomes "upload_max_filesize = 10M".

Após o upload de img O TMP_name de $FILE retorna como nulo bloqueando o upload.
O motivo foi o tamanho do arquivo, o padrão do php.ini é 2 MB, então é preciso alterar o código no php.ini para que "upload_max_filesize = 2M" se torne "upload_max_filesize = 10M".