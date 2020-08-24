 <h3><p>The Uniform Server 64bit x64 php apache</p></h3>
<ol>
  <li><p>
    Download Apache x64, extract to <b>core/apache2</b><br>
    Server Version: Apache/2.4.46 (Win64) PHP/7.4.5 OpenSSL/1.1.1g<br>
    Apache Lounge VS16 Server built: Aug 2 2020 10:21:32<br>
    https://www.apachelounge.com/download/VS16/binaries/httpd-2.4.46-win64-VS16.zip
  </p></li>
  <li><p>
    Download PHP 7.4.5 x64 64bit, extract to <b>core/php74</b><br>
    PHP Version 7.4.5 x64 Visual C++ 2017<br>
    <a href="https://windows.php.net/downloads/releases/archives/php-7.4.5-Win32-vc15-x64.zip">Download PHP Version 7.4.5</a>
    <a href="https://aka.ms/vs/16/release/vc_redist.x64.exe">Download Visual Studio 2015-2019</a>
    </p></li>
 <li><p>
    Download PHP 5.6.9 x64 64bit, extract to <b>core/php56</b><br>
    PHP Version 5.6.9 x64 Visual C++ 2012 <br>
    <ol>
     <ul><a href="https://windows.php.net/downloads/releases/archives/php-7.4.5-Win32-vc15-x64.zip">Download PHP Version 5.6.9</a></ul>
     <ul><a href="https://my.visualstudio.com/Downloads?pid=1452">Download Visual Studio 2012</a></ul>
  </ol>
    </p></li>
  <li><p>
    Rename core/apache2/bin/httpd.exe to core/apache2/bin/httpd_z.exe
    </p></li>
  <li><p><ol>
   <lu>
    Rename core/php74/ext to core/php74/extensions</lu>
   <lu>
    Rename core/php56/ext to core/php56/extensions</lu>
   </ol>
    </p></li>
  </ol>
