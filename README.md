# Task_6
Exercise on API using Twitter4J

### Twitter OAuth Token
* log in ke akun Twitter
* buka halaman [apps.twitter.com] (apps.twitter.com)
* buatlag aplikasi baru dengan mengekklik create new App<br>
	![b01] (/asset/b01.PNG) <br>
* tuliskan nama dan deskripsi aplikasi, tuliskan website aplikasi (jika ada) atau tuliskan alamat URL akun Twitter masing-masing<br>
	![b02] (/asset/b02.PNG) <br>
* check Developer Agreement, dan klik Create your Twitter application<br>
	![b03] (/asset/b03.PNG) <br>
* setelah aplikasi dibuat, navigasikan ke tab Keys and Access Tokens
* akan terlihat 25-character Consumer Key dan 50-character Consumer Secret aplikasi yang baru dibuat<br>
	![b04] (/asset/b04.PNG) <br>
* scroll down dan klik create your new access token<br>
	![b05] (/asset/b05.PNG) <br>
* akan terlihat 49-digit-dash-character Access Token dan 45-character Access Token Secret<br>
	![b06] (/asset/b06.PNG) <br>
* buatlah sebuah file text dengan filename twitter4j.properties<br>
	![b07] (/asset/b07.PNG) <br>
* tuliskan Consumer Key, Consumer Secret, Access Token, and Access Token Secret ke dalam twitter4j.properties sebagai berikut<br>
	![b08] (/asset/b08.PNG) <br>
* twitter4j.properties telah terdaftar di dalam .gitignore, sehingga file twitter4j.properties tidak akan disinkronisasikan (push) ke repositori
* see more [here] (https://dev.twitter.com/oauth/overview/application-owner-access-tokens)


### Aplikasi Java Twitter
Buatlah aplikasi java twitter yaitu aplikasi yang untuk mengakses social media twitter melaui apikasi java. Aplikasi java twitter ini memiliki spesifikasi sebagai berikut

#### 1. TwitterModel.java
* download library for Twitter API dari [Twitter4J] (http://twitter4j.org)
* temukan lib jar twitter4j-core-4.0.1.jar
* Buatlah sebuah project NetBeans
* Copy kan library twitter4j-core-4.0.1.jar dan twitter4j.properties pada folder project anda
* Tambahkan (add) seluruh library tersebut pada project NetBeans Anda
* Buatlah sebuah kelas dengan nama TwitterModel.java dengan spesifikasi sbb:<br>
	![01] (/asset/01.PNG) <br>
* Tambahkan import twitter4j<br>
	![02] (/asset/02.PNG) <br>


<br>
	![03] (/asset/03.PNG) <br>