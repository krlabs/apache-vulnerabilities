# Список вразливостей веб-сервера Apache

Публікується з метою контролю безпеки сайтів на базі веб-серверів Apache. На замітку дослідникам та власникам електронних ресурсів.

Дані вразливості були виявлені дослідниками KR. Laboratories в ході глобального аудиту ресурсів інтернет-мережі УАРНЕТ й можуть бути використані як легітимними пентестерами, так і зловмисниками для проведення таких атак як: переповнення буфера (buffer overflow), Denial of Service / Distributed Denial of Service (DoS/DDoS), розкриття конфіденційної інформації (expose sesitive information / information disclosure), пошкодження даних і помилки конфігураці та багато інших.   

Ми рекомендуємо українським веб-майстрам і системним адміністраторам регулярно оновлювати серверне програмне забезпечення та використовувати наші рекомендації щодо кібербезпеки, аби мінімізувати потенційні ризики.  

З приводу захисту веб-серверів пишіть нам на електронну скриньку: security[@]kr-labs.com.ua

| **CVE Ідентифікатор** | **Опис** | **Exploit** |
|------------------------|----------|-------------|
| [**CVE-2007-5000**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-5000) | Вразливість у модулі mod_imagemap дозволяє провести віддалену XSS-атаку. | [Публічний експлойт](http://example.com/exploit/6420) |
| [**CVE-2007-6420**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6420) | Вразливість у модулі mod_proxy_balancer дозволяє провести CSRF-атаку на серверах, де дозволено використання цього модуля. |
| [**CVE-2007-6421**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6421) | Вразливість у модулі mod_proxy_balancer дозволяє провести XSS-атаку. |
| [**CVE-2007-6422**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6422) | Вразливість у модулі mod_proxy_balancer дозволяє викликати відмову в обслуговуванні. |
| [**CVE-2007-6399**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6399) | Вразливість у модулі mod_status дозволяє провести XSS-атаку. |
| [**CVE-2008-0005**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-0005) | Вразливість у модулі mod_proxy_ftp дозволяє провести XSS-атаку на сервери з включеним модулем. |
| [**CVE-2008-0456**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-0456) | Вразливість у модулі mod_negotiation дозволяє провести response splitting атаку. |
| [**CVE-2008-2364**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-2364) | Вразливість у модулі mod_proxy_http дозволяє віддаленому атакуючому викликати відмову в обслуговуванні (DoS). |
| [**CVE-2008-2939**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-2939) | Вразливість дозволяє впровадити сценарій і провести XSS-атаку через FTP-шлях. |
| [**CVE-2009-1890**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-1890) | Вразливість у модулі mod_proxy дозволяє викликати відмову в обслуговуванні. |
| [**CVE-2009-1891**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-1891) | Вразливість у модулі mod_deflate дозволяє викликати відмову в обслуговуванні. |
| [**CVE-2009-3094**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3094) | Вразливість у модулі mod_proxy_ftp може призводити до відмови в обслуговуванні. |
| [**CVE-2009-3095**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3095) | Вразливість у модулі mod_proxy_ftp дозволяє віддаленому атакуючому посилати довільні команди FTP-серверу. |
| [**CVE-2009-3560**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3560) | Дозволяє атакуючому, залежному від контексту, викликати відмову в обслуговуванні («падіння» застосунку) за допомогою спеціально створеного XML-документа з неправильною UTF-8 послідовністю, яка викликає переповнення буфера. Вразливість пов'язана з функцією doProlog у бібліотеці /xmlparse.c. |
| [**CVE-2009-3720**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3720) | Дозволяє атакуючому, залежному від контексту, викликати відмову в обслуговуванні («падіння» застосунку) за допомогою спеціально створеного XML-документа з неправильною UTF-8 послідовністю, яка викликає переповнення буфера. |
| [**CVE-2010-0408**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-0408) | Вразливість у модулі mod_proxy_ajp дозволяє викликати відмову в обслуговуванні. |
| [**CVE-2010-1452**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-1452) | Вразливість у модулях mod_cache та mod_dav дозволяє викликати відмову в обслуговуванні. |
| [**CVE-2010-1623**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-1623) | Дозволяє зловмиснику (віддалено) викликати відмову в обслуговуванні (надмірне споживання пам’яті). |
| [**CVE-2011-0419**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-0419) | Дозволяє атакуючому, залежному від контексту, викликати відмову в обслуговуванні (CPU та пам’ять) через послідовність «*?» у першому аргументі, як показали атаки на mod_autoindex у HTTPD. |
| [**CVE-2011-3192**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3192) | Дозволяє зловмиснику (віддалено) викликати відмову в обслуговуванні (пам’ять і процесор) через заголовок Range, який виражає кілька перекриваючихся діапазонів. | [Публічний експлойт](https://github.com/limkokholefork/CVE-2011-3192) |
| [**CVE-2011-3348**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3348) | Дозволяє зловмиснику (віддалено) викликати відмову в обслуговуванні (тимчасовий «стан помилки» на внутрішньому сервері) через неправильно сформований HTTP-запит. |
| [**CVE-2011-3368**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3368) | Дозволяє зловмиснику (віддалено) відправити запит на сервери внутрішньої мережі. |
| [**CVE-2011-3607**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3607) | Дозволяє локальному користувачу підвищити свої права в системі. |
| [**CVE-2011-3639**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3639) | Вразливість дозволяє викликати відмову в обслуговуванні через використання HTTP/0.9. |
| [**CVE-2011-4317**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-4317) | Вразливість у модулі proxy дозволяє обходити обмеження доступу. |
| [**CVE-2011-4415**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-4415) | Локальний користувач може викликати відмову в обслуговуванні. |
| [**CVE-2012-0031**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0031) | Дозволяє локальному користувачу викликати «відмову в обслуговуванні». |
| [**CVE-2012-0053**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0053) | Дозволяє зловмиснику отримати HTTPOnly cookies за допомогою спеціально сформованого веб-скрипта. |
| [**CVE-2012-0031**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0031) | Локальний користувач може викликати відмову в обслуговуванні. |
| [**CVE-2012-2687**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-2687) | Вразливість у модулі mod_negotiation дозволяє провести XSS-атаку. |
| [**CVE-2012-0883**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0883) | Локальний користувач може підвищити привілеї. |
| [**CVE-2016-8740**](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-8740) | Локальний користувач може підвищити привілеї. | [Публічний експлойт](https://www.exploit-db.com/exploits/40909) |

### Джерела
- [TrustWave. Hunting For Integer Overflows In Web Servers](https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/hunting-for-integer-overflows-in-web-servers/)
- [PICUS.Five Ways to Simulate Apache CVE-2021-41773 Exploits](https://www.picussecurity.com/resource/blog/simulate-apache-cve-2021-41773-exploits-vulnerability)
- [Qualys Community.Apache HTTP Server Path Traversal & Remote Code Execution (CVE-2021-41773 & CVE-2021-42013)](https://blog.qualys.com/vulnerabilities-threat-research/2021/10/27/apache-http-server-path-traversal-remote-code-execution-cve-2021-41773-cve-2021-42013)
- [Medium.CVE-2024–40725 and CVE-2024–40898: Critical Vulnerabilities in Apache HTTP Server](https://infosecwriteups.com/cve-2024-40725-and-cve-2024-40898-critical-vulnerabilities-in-apache-http-server-d292084255dc)
- [Medium.Exploit Apache HTTP Server Vulnerabilities](https://medium.com/@sebastienwebdev/exploit-apache-http-server-vulnerabilities-a18049ee1f05)
- [ExploitDB.Apache Vulnerabilities](https://www.exploit-db.com/?search=apache)
- {ZeroDay.cz.0-Zero-Day Vulnerabilities](https://www.zero-day.cz)
