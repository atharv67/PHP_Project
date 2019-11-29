# PHP_Project
TE-IT

<br/>
<b>Pre-requisite-</b>
<ul>
  <li>XAMPP Software</li>
  <ul>
    <li>Apache</li>
    <li>MySQL</li>
  </ul>
  <li>Composer</li>
</ul>
<br/>
<b>Settings</b>
<ul>
  <li>Put all the files in the Xampp/htdocs folder (<b>Can be accessed as url: localhost/Landing_Page/home.php</b>)</li>
  <li>Changes in my.ini file (<b>Can be accessed through Xampp Control Panel MySQL-Config or Xampp/mysql/bin/my.ini</b>)</li>
  <ul>
    <li>max_allowed_packet = 64M</li>
    <li>innodb_log_file_size = 256M</li>
    <li>innodb_lock_wait_timeout = 500</li>
  </ul>
  <li>Changes in php.ini file (<b>Can be accessed through Xampp Control Panel Apache-Config or Xampp/php/php.ini</b>)</li>
  <ul>
    <li>max_execution_time=300</li>
    <li>display_errors=Off</li>
    <li>post_max_size=1280M</li>
    <li>upload_max_filesize=1280M</li>
    <li>sendmail_path = "\"..\Xampp\sendmail\sendmail.exe\" -t" (<b>.. has to be replaced by whole path</b>)</li>
  </ul>
</ul>
