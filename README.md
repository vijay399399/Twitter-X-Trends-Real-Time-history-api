# Twitter-X-Trends-Real-Time-history-api
Get Real Time Twitter / X Trends with Rich data of 64 countries &amp; 460 Cities which updated hourly. Other json api Endpoint is past 48 hours , past 30 days trends with volume and tweet name.
<h3>Usage Api</h3>
<pre>
  <code>
    curl --request GET \
	--url 'https://twitter-x-trends-real-time.p.rapidapi.com/api/?name=united-states&tag=past48hours' \
	--header 'x-rapidapi-host: twitter-x-trends-real-time.p.rapidapi.com' \
	--header 'x-rapidapi-key: RAPIDAPI_KEY_HERE'
  </code>
</pre>
<div class="markdown markdown [&amp;_h1_a]:!text-4xl [&amp;_h1_a]:!font-semibold [&amp;_h2_a]:!text-3xl [&amp;_h2_a]:!font-semibold [&amp;_h3_a]:!text-2xl [&amp;_h3_a]:!font-semibold [&amp;_h4_a]:!text-xl [&amp;_h4_a]:!font-semibold [&amp;_h5_a]:!text-lg [&amp;_h5_a]:!font-semibold [&amp;_h6_a]:!text-base [&amp;_h6_a]:!font-semibold"><h2>Api Documentation</h2>
<h3>Countries and city names </h3>
This city and countries real time , past 48 hours and past 30 days trends available. Use exact <b>name</b> parameter for fetch.
<pre><code>worldwide
algeria
algiers
argentina
mendoza
cordoba
rosario
buenos-aires
australia
perth
adelaide
brisbane
canberra
darwin
melbourne
sydney
austria
vienna
bahrain
belarus
brest
grodno
gomel
minsk
belgium
brazil
brasilia
belem
belo-horizonte
curitiba
porto-alegre
recife
rio-de-janeiro
salvador
sao-paulo
campinas
fortaleza
goiania
manaus
sao-luis
guarulhos
canada
winnipeg
ottawa
quebec
montreal
toronto
edmonton
calgary
vancouver
chile
santiago
concepcion
valparaiso
colombia
bogota
cali
medell
barranquilla
denmark
dominican-republic
santo-domingo
ecuador
quito
guayaquil
egypt
giza
cairo
alexandria
france
bordeaux
lille
lyon
marseille
montpellier
nantes
paris
rennes
strasbourg
toulouse
germany
berlin
bremen
dortmund
dresden
dusseldorf
essen
frankfurt
hamburg
cologne
leipzig
munich
stuttgart
ghana
accra
kumasi
greece
athens
thessaloniki
guatemala
guatemala-city
india
nagpur
lucknow
kanpur
patna
ranchi
kolkata
srinagar
amritsar
jaipur
ahmedabad
rajkot
surat
bhopal
indore
thane
mumbai
pune
hyderabad
bangalore
chennai
delhi
indonesia
bekasi
depok
pekanbaru
surabaya
makassar
bandung
jakarta
medan
palembang
semarang
tangerang
ireland
cork
dublin
galway
israel
haifa
tel-aviv
jerusalem
italy
bologna
genoa
milan
naples
palermo
rome
turin
japan
kitakyushu
saitama
chiba
fukuoka
hamamatsu
hiroshima
kawasaki
kobe
kumamoto
nagoya
niigata
sagamihara
sapporo
sendai
takamatsu
tokyo
yokohama
okinawa
osaka
kyoto
okayama
jordan
amman
kenya
mombasa
nairobi
korea
goyang
yongin
ansan
bucheon
busan
changwon
daegu
gwangju
incheon
seongnam
suwon
ulsan
seoul
daejeon
kuwait
latvia
riga
lebanon
malaysia
kajang
ipoh
johor-bahru
klang
kuala-lumpur
petaling
hulu-langat
mexico
acapulco
aguascalientes
chihuahua
mexico-city
ciudad-juarez
nezahualcoyotl
culiacan
ecatepec-de-morelos
guadalajara
hermosillo
merida
mexicali
monterrey
morelia
puebla
queretaro
saltillo
san-luis-potos
tijuana
toluca
zapopan
netherlands
den-haag
amsterdam
rotterdam
utrecht
new-zealand
auckland
nigeria
benin-city
ibadan
kaduna
kano
lagos
port-harcourt
norway
bergen
oslo
oman
muscat
pakistan
karachi
lahore
multan
rawalpindi
faisalabad
panama
peru
lima
philippines
calocan
makati
pasig
taguig
antipolo
cagayan-de-oro
cebu-city
davao-city
manila
quezon-city
zamboanga-city
poland
gdansk
krakow
lodz
poznan
warsaw
wroclaw
portugal
puerto-rico
qatar
russia
chelyabinsk
khabarovsk
krasnodar
krasnoyarsk
samara
voronezh
yekaterinburg
irkutsk
kazan
moscow
nizhny-novgorod
novosibirsk
omsk
perm
saint-petersburg
ufa
vladivostok
volgograd
saudi-arabia
medina
dammam
riyadh
jeddah
mecca
ahsa
singapore
south-africa
durban
johannesburg
port-elizabeth
pretoria
soweto
cape-town
spain
barcelona
bilbao
las-palmas
madrid
malaga
murcia
palma
seville
valencia
zaragoza
sweden
gothenburg
stockholm
switzerland
geneva
lausanne
zurich
thailand
bangkok
turkey
mersin
adana
ankara
antalya
bursa
diyarbakir
eskisehir
gaziantep
istanbul
izmir
kayseri
konya
ukraine
dnipropetrovsk
donetsk
kharkiv
kyiv
lviv
odesa
zaporozhye
united-arab-emirates
sharjah
abu-dhabi
dubai
united-kingdom
birmingham
blackpool
bournemouth
brighton
bristol
cardiff
coventry
derby
edinburgh
glasgow
hull
leeds
leicester
liverpool
manchester
middlesbrough
newcastle
nottingham
plymouth
portsmouth
preston
sheffield
swansea
london
belfast
united-states
albuquerque
atlanta
austin
baltimore
baton-rouge
birmingham
boston
charlotte
chicago
cincinnati
cleveland
colorado-springs
columbus
denver
detroit
el-paso
fresno
greensboro
harrisburg
honolulu
houston
indianapolis
jackson
jacksonville
kansas-city
las-vegas
long-beach
los-angeles
louisville
memphis
mesa
miami
milwaukee
minneapolis
nashville
new-haven
new-orleans
new-york
norfolk
oklahoma-city
omaha
orlando
philadelphia
phoenix
pittsburgh
portland
providence
raleigh
richmond
sacramento
st.-louis
salt-lake-city
san-antonio
san-diego
san-francisco
san-jose
seattle
tallahassee
tampa
tucson
virginia-beach
washington
venezuela
caracas
maracaibo
maracay
valencia
barcelona
ciudad-guayana
turmero
barquisimeto
matur
vietnam
hanoi
hai-phong
can-tho
da-nang
ho-chi-minh-city
</code></pre>
<h3>Time period</h3>
Use this <b>tag</b> parameter
<pre><code>realtime
past48hours
past30days
</code></pre></div>
<h3>Response</h3>
<pre>
  <code>
    [
  {
    "data": {
      "trends": [
        {
          "name": "Ravens",
          "tweet_volume": "127K"
        },
        {
          "name": "Lamar",
          "tweet_volume": "75K"
        },
        {
          "name": "Tyler Loop",
          "tweet_volume": "24K"
        },
        {
          "name": "Justin Tucker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#HereWeGo",
          "tweet_volume": "21K"
        },
        {
          "name": "Aaron Rodgers",
          "tweet_volume": "20K"
        },
        {
          "name": "Boswell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Harbaugh",
          "tweet_volume": "17K"
        },
        {
          "name": "Kickers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Zay Flowers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tomlin",
          "tweet_volume": "21K"
        },
        {
          "name": "#SNFonNBC",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jalen Ramsey",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#BALvsPIT",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Texans",
          "tweet_volume": "40K"
        },
        {
          "name": "Billy Cundiff",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "AFC North",
          "tweet_volume": "27K"
        },
        {
          "name": "Derrick Henry",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Zach Orr",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Isaiah Likely",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "HE MISSED IT",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kyle Hamilton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Arthur Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#SundayNightFootball",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Packers",
          "tweet_volume": "46K"
        },
        {
          "name": "Calvin Austin",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Highsmith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bears",
          "tweet_volume": "88K"
        },
        {
          "name": "KINGS OF THE NORTH",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Mike Tirico",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Roquan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Eagles",
          "tweet_volume": "83K"
        },
        {
          "name": "WHAT A GAME",
          "tweet_volume": "40K"
        },
        {
          "name": "#BaddiesUSA",
          "tweet_volume": "12K"
        },
        {
          "name": "Huntley",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Marlon Humphrey",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Collinsworth",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Devin Booker",
          "tweet_volume": "12K"
        },
        {
          "name": "Jets",
          "tweet_volume": "68K"
        },
        {
          "name": "WIDE RIGHT",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Patrick Queen",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cam Heyward",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Mark Andrews",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cancun",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Harbs",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Lindsey Graham",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Teryl Austin",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Raheem Morris",
          "tweet_volume": "17K"
        },
        {
          "name": "Gainwell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Monken",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767596043
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Ravens",
          "tweet_volume": "71K"
        },
        {
          "name": "Ravens",
          "tweet_volume": "71K"
        },
        {
          "name": "Lamar",
          "tweet_volume": "45K"
        },
        {
          "name": "Boswell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rodgers",
          "tweet_volume": "24K"
        },
        {
          "name": "Zay Flowers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jalen Ramsey",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#HereWeGo",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tyler Loop",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#BALvsPIT",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tomlin",
          "tweet_volume": "13K"
        },
        {
          "name": "#SNFonNBC",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Isaiah Likely",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pittsburgh",
          "tweet_volume": "12K"
        },
        {
          "name": "Arthur Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kickers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Highsmith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kyle Hamilton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Zach Orr",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Justin Tucker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Patrick Queen",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bears",
          "tweet_volume": "85K"
        },
        {
          "name": "Packers",
          "tweet_volume": "44K"
        },
        {
          "name": "Harbaugh",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Devin Booker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Calvin Austin",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Marlon Humphrey",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "HE MISSED IT",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Eagles",
          "tweet_volume": "80K"
        },
        {
          "name": "Collinsworth",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cam Heyward",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#RHOP",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Raheem Morris",
          "tweet_volume": "16K"
        },
        {
          "name": "#BaddiesUSA",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Teryl Austin",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jets",
          "tweet_volume": "65K"
        },
        {
          "name": "Gainwell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jaylen Warren",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Renegade",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "TJ Watt",
          "tweet_volume": "11K"
        },
        {
          "name": "Roquan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "AFC North",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Suns",
          "tweet_volume": "22K"
        },
        {
          "name": "Derrick Henry",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Hopkins",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Penix",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dillon Brooks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rich McKay",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Muth",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jordan Goodwin",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767589104
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Ravens",
          "tweet_volume": "55K"
        },
        {
          "name": "Steelers",
          "tweet_volume": "66K"
        },
        {
          "name": "Lamar",
          "tweet_volume": "25K"
        },
        {
          "name": "Rodgers",
          "tweet_volume": "16K"
        },
        {
          "name": "Arthur Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#HereWeGo",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bears",
          "tweet_volume": "84K"
        },
        {
          "name": "Tomlin",
          "tweet_volume": "11K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "79K"
        },
        {
          "name": "Packers",
          "tweet_volume": "43K"
        },
        {
          "name": "Marlon Humphrey",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kyle Hamilton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Devin Booker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Raheem Morris",
          "tweet_volume": "15K"
        },
        {
          "name": "#BALvsPIT",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#CriticsChoice",
          "tweet_volume": "49K"
        },
        {
          "name": "#BaddiesUSA",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#RHOP",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cam Heyward",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jets",
          "tweet_volume": "64K"
        },
        {
          "name": "TJ Watt",
          "tweet_volume": "10K"
        },
        {
          "name": "Harbaugh",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Penix",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ringo",
          "tweet_volume": "18K"
        },
        {
          "name": "Collinsworth",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Gainwell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rich McKay",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dillon Brooks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Raiders",
          "tweet_volume": "49K"
        },
        {
          "name": "Lions",
          "tweet_volume": "58K"
        },
        {
          "name": "Broncos",
          "tweet_volume": "40K"
        },
        {
          "name": "Luke Hughes",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jordan Goodwin",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Arthur Blank",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Texans",
          "tweet_volume": "34K"
        },
        {
          "name": "Gizelle",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Falcons",
          "tweet_volume": "56K"
        },
        {
          "name": "Greenland",
          "tweet_volume": "238K"
        },
        {
          "name": "Terry Fontenot",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Banjo Kazooie",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "McKee",
          "tweet_volume": "11K"
        },
        {
          "name": "Highsmith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Matt Ryan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jonnu Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Muth",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Toya",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Zach Orr",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jags",
          "tweet_volume": "11K"
        },
        {
          "name": "Jaylen Warren",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ramsey",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767585359
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Bears",
          "tweet_volume": "70K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "66K"
        },
        {
          "name": "Ringo",
          "tweet_volume": "17K"
        },
        {
          "name": "Lions",
          "tweet_volume": "52K"
        },
        {
          "name": "McKee",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Broncos",
          "tweet_volume": "29K"
        },
        {
          "name": "Raiders",
          "tweet_volume": "42K"
        },
        {
          "name": "Jets",
          "tweet_volume": "53K"
        },
        {
          "name": "Dan Campbell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sirianni",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#OnePride",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ben Johnson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Josh Johnson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cardinals",
          "tweet_volume": "10K"
        },
        {
          "name": "#CriticsChoiceAwards",
          "tweet_volume": "52K"
        },
        {
          "name": "Aaron Glenn",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Trey Lance",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ballard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Commanders",
          "tweet_volume": "16K"
        },
        {
          "name": "Giants",
          "tweet_volume": "61K"
        },
        {
          "name": "Michael Wilson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Greenland",
          "tweet_volume": "211K"
        },
        {
          "name": "Texans",
          "tweet_volume": "28K"
        },
        {
          "name": "#RaiderNation",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Colts",
          "tweet_volume": "29K"
        },
        {
          "name": "Browns",
          "tweet_volume": "54K"
        },
        {
          "name": "#RaiseHail",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jags",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sean Payton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Blakes",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#HereWeGo",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Myles",
          "tweet_volume": "59K"
        },
        {
          "name": "Colston Loveland",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dolphins",
          "tweet_volume": "13K"
        },
        {
          "name": "Tank",
          "tweet_volume": "41K"
        },
        {
          "name": "Jaylon Johnson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dennis Allen",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cancun",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Daniel Carlson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Strahan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bengals",
          "tweet_volume": "22K"
        },
        {
          "name": "Roman Wilson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ewers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kevin Byard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Craigslist",
          "tweet_volume": "16K"
        },
        {
          "name": "Jalyx Hunt",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sarah Snook",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Landy",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jaguars",
          "tweet_volume": "38K"
        },
        {
          "name": "Mitch Trubisky",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767577828
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Giants",
          "tweet_volume": "50K"
        },
        {
          "name": "Myles Garrett",
          "tweet_volume": "33K"
        },
        {
          "name": "FINALLY DID IT",
          "tweet_volume": "1.6M"
        },
        {
          "name": "Colts",
          "tweet_volume": "19K"
        },
        {
          "name": "Cowboys",
          "tweet_volume": "21K"
        },
        {
          "name": "Bengals",
          "tweet_volume": "17K"
        },
        {
          "name": "The PENGU",
          "tweet_volume": "241K"
        },
        {
          "name": "Falcons",
          "tweet_volume": "33K"
        },
        {
          "name": "Riley Leonard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Burrow",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tyler Shough",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#KeepPounding",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Alec Pierce",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Saints",
          "tweet_volume": "45K"
        },
        {
          "name": "#Browns",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "The BONK",
          "tweet_volume": "174K"
        },
        {
          "name": "#DawgPound",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cam Little",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Strahan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "NFC South",
          "tweet_volume": "18K"
        },
        {
          "name": "Favre",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "The Jupiter",
          "tweet_volume": "292K"
        },
        {
          "name": "Panthers",
          "tweet_volume": "72K"
        },
        {
          "name": "Zac Taylor",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#DUUUVAL",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Harrison Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Vikings",
          "tweet_volume": "26K"
        },
        {
          "name": "#Skol",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jaguars",
          "tweet_volume": "20K"
        },
        {
          "name": "Dee Alford",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Chase Young",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Greenland",
          "tweet_volume": "171K"
        },
        {
          "name": "Jaxson Dart",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Joe Milton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ronnie Bell",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Clowney",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "JJ McCarthy",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Max Brosmer",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Go Birds",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "TJ Watt",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Clayton Tune",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ballard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Raheem",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Daniss Jenkins",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bowles",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Stefanski",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Chelsea",
          "tweet_volume": "240K"
        },
        {
          "name": "Bucs",
          "tweet_volume": "30K"
        },
        {
          "name": "Kenneth Murray",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Brandon Allen",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767565260
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "FINALLY DID IT",
          "tweet_volume": "1.6M"
        },
        {
          "name": "The PENGU",
          "tweet_volume": "219K"
        },
        {
          "name": "Cam Little",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "The Jupiter",
          "tweet_volume": "250K"
        },
        {
          "name": "The AsterDEX",
          "tweet_volume": "95K"
        },
        {
          "name": "Riley Leonard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "The BONK",
          "tweet_volume": "174K"
        },
        {
          "name": "The WET",
          "tweet_volume": "33K"
        },
        {
          "name": "Bengals",
          "tweet_volume": "10K"
        },
        {
          "name": "Chelsea",
          "tweet_volume": "205K"
        },
        {
          "name": "JJ McCarthy",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Alec Pierce",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Saints",
          "tweet_volume": "36K"
        },
        {
          "name": "Cam Ward",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Zac Taylor",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#Skol",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jaxson Dart",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jaydon Blue",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tee Higgins",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Brandon Allen",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kenneth Murray",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#DUUUVAL",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Enzo",
          "tweet_volume": "46K"
        },
        {
          "name": "Devin Bush",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pedro Neto",
          "tweet_volume": "12K"
        },
        {
          "name": "Joe Milton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#DawgPound",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Clayton Tune",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Juwan Johnson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pittman",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "CJ Ham",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#NYGiants",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kirk Cousins",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Greenland",
          "tweet_volume": "145K"
        },
        {
          "name": "Rubio",
          "tweet_volume": "533K"
        },
        {
          "name": "Delap",
          "tweet_volume": "10K"
        },
        {
          "name": "Dallas Turner",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Parker Washington",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#MCICHE",
          "tweet_volume": "24K"
        },
        {
          "name": "Clowney",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Noah Fant",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "McPherson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Justin Jefferson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Antonio Johnson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Seton Hall",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cabrera",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Liverpool",
          "tweet_volume": "102K"
        },
        {
          "name": "Creighton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cherki",
          "tweet_volume": "12K"
        },
        {
          "name": "Myles Garrett",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767558230
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "JJ McCarthy",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Fulham",
          "tweet_volume": "35K"
        },
        {
          "name": "Liverpool",
          "tweet_volume": "86K"
        },
        {
          "name": "Gonzalo",
          "tweet_volume": "70K"
        },
        {
          "name": "Rubio",
          "tweet_volume": "492K"
        },
        {
          "name": "Juwan Johnson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Saints",
          "tweet_volume": "29K"
        },
        {
          "name": "Mbappe",
          "tweet_volume": "34K"
        },
        {
          "name": "Harrison Reed",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#FULLIV",
          "tweet_volume": "16K"
        },
        {
          "name": "Go Bills",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Wirtz",
          "tweet_volume": "19K"
        },
        {
          "name": "#BTSComeback2026",
          "tweet_volume": "127K"
        },
        {
          "name": "Vini",
          "tweet_volume": "19K"
        },
        {
          "name": "Slot",
          "tweet_volume": "69K"
        },
        {
          "name": "#sundayvibes",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Gakpo",
          "tweet_volume": "16K"
        },
        {
          "name": "Cam Jordan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "No Kings",
          "tweet_volume": "48K"
        },
        {
          "name": "Good Sunday",
          "tweet_volume": "94K"
        },
        {
          "name": "Joao Pedro",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Margaret Brennan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Clayton Tune",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "First Sunday",
          "tweet_volume": "48K"
        },
        {
          "name": "Rodrygo",
          "tweet_volume": "14K"
        },
        {
          "name": "Gowdy",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dalton Schultz",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Betis",
          "tweet_volume": "33K"
        },
        {
          "name": "Creighton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#NFLRedZone",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Xabi",
          "tweet_volume": "11K"
        },
        {
          "name": "#MCICHE",
          "tweet_volume": "13K"
        },
        {
          "name": "Amorim",
          "tweet_volume": "65K"
        },
        {
          "name": "BTS IS BACK",
          "tweet_volume": "51K"
        },
        {
          "name": "Paul DeJong",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Asencio",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Igor Thiago",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "159K"
        },
        {
          "name": "Who Dey",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tatum",
          "tweet_volume": "12K"
        },
        {
          "name": "Sunday Funday",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Richarlison",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Frimpong",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jay Glazer",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Meet the Press",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "14 TRACKS",
          "tweet_volume": "98K"
        },
        {
          "name": "Harry Wilson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Stefanski",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Thomas Frank",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "BTS THE 5TH ALBUM",
          "tweet_volume": "65K"
        }
      ],
      "timestamp": 1767551369
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#BTSComeback2026",
          "tweet_volume": "97K"
        },
        {
          "name": "Good Sunday",
          "tweet_volume": "89K"
        },
        {
          "name": "#sundayvibes",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#FULLIV",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Slot",
          "tweet_volume": "54K"
        },
        {
          "name": "Sesko",
          "tweet_volume": "23K"
        },
        {
          "name": "Gonzalo",
          "tweet_volume": "20K"
        },
        {
          "name": "14 TRACKS",
          "tweet_volume": "70K"
        },
        {
          "name": "Ben Davies",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "BTS IS BACK",
          "tweet_volume": "30K"
        },
        {
          "name": "First Sunday",
          "tweet_volume": "44K"
        },
        {
          "name": "No Kings",
          "tweet_volume": "47K"
        },
        {
          "name": "Leeds",
          "tweet_volume": "91K"
        },
        {
          "name": "Rubio",
          "tweet_volume": "490K"
        },
        {
          "name": "Zirkzee",
          "tweet_volume": "11K"
        },
        {
          "name": "Fulham",
          "tweet_volume": "18K"
        },
        {
          "name": "Harry Wilson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "MOCK",
          "tweet_volume": "12K"
        },
        {
          "name": "Gakpo",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "BTS IS COMING",
          "tweet_volume": "133K"
        },
        {
          "name": "#LEEMUN",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cunha",
          "tweet_volume": "20K"
        },
        {
          "name": "Gowdy",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sunday Funday",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Meet the Press",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tatum",
          "tweet_volume": "11K"
        },
        {
          "name": "Tim Kaine",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#SundayMotivation",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "162K"
        },
        {
          "name": "Muhammad Qasim",
          "tweet_volume": "31K"
        },
        {
          "name": "Colton Joseph",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dorgu",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rodrygo",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dalot",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Blessed Sunday",
          "tweet_volume": "21K"
        },
        {
          "name": "The Ralph",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Konate",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "BTS BTS BTS",
          "tweet_volume": "841K"
        },
        {
          "name": "Russia and China",
          "tweet_volume": "161K"
        },
        {
          "name": "Chiesa",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "1st Sunday",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Singularity",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tanahashi",
          "tweet_volume": "25K"
        },
        {
          "name": "Good Morning Dan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Little Marco",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rear Admiral",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Brentford",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Lammens",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Hojlund",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Exxon",
          "tweet_volume": "16K"
        }
      ],
      "timestamp": 1767546156
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#njwk20",
          "tweet_volume": "113K"
        },
        {
          "name": "Tanahashi",
          "tweet_volume": "12K"
        },
        {
          "name": "Ibushi",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "JAY WHITE",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Shibata",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Aaron Wolf",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "GO ACE",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jake Lee",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tsuji",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sent with DataHaven",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#WrestleKingdom20",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Camp Haven",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Good Sunday",
          "tweet_volume": "61K"
        },
        {
          "name": "Andrade",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jaylen Brown",
          "tweet_volume": "18K"
        },
        {
          "name": "#棚橋引退",
          "tweet_volume": "86K"
        },
        {
          "name": "Ospreay",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Seahawks",
          "tweet_volume": "95K"
        },
        {
          "name": "Naito",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "49ers",
          "tweet_volume": "65K"
        },
        {
          "name": "Tokyo Dome",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Shinsuke",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Gedo",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Nakamura",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "United Empire",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "SANADA",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Niners",
          "tweet_volume": "15K"
        },
        {
          "name": "New Japan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Celtics",
          "tweet_volume": "17K"
        },
        {
          "name": "#Toonami",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Syuri",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sam Darnold",
          "tweet_volume": "11K"
        },
        {
          "name": "Saya Kamitani",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "No Kings",
          "tweet_volume": "39K"
        },
        {
          "name": "SDSU",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#DifferentHere",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Mike Macdonald",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Boise State",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Shanahan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pearsall",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Trent",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cheese",
          "tweet_volume": "34K"
        },
        {
          "name": "NFC West",
          "tweet_volume": "14K"
        },
        {
          "name": "Bosa",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "John Schneider",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Lenoir",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Marshawn",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "San Diego State",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Gilligan's Island",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "South Korea",
          "tweet_volume": "49K"
        }
      ],
      "timestamp": 1767526516
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#njwk20",
          "tweet_volume": "58K"
        },
        {
          "name": "Jake Lee",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Andrade",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Seahawks",
          "tweet_volume": "91K"
        },
        {
          "name": "Jaylen Brown",
          "tweet_volume": "16K"
        },
        {
          "name": "Niners",
          "tweet_volume": "14K"
        },
        {
          "name": "Hiromu",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#WrestleKingdom20",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "United Empire",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Celtics",
          "tweet_volume": "15K"
        },
        {
          "name": "Darnold",
          "tweet_volume": "17K"
        },
        {
          "name": "Syuri",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#Toonami",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Finlay",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Saya Kamitani",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "SANADA",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "GO ACE",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tokyo Dome",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#Mashle",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "SDSU",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Mike Macdonald",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Chris Brookes",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#GoHawks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Boise State",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Shanahan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "NFC West",
          "tweet_volume": "13K"
        },
        {
          "name": "Trent",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Aztecs",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pearsall",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "San Diego State",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Greenland",
          "tweet_volume": "102K"
        },
        {
          "name": "Tanahashi",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "New Japan",
          "tweet_volume": "11K"
        },
        {
          "name": "John Collins",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "No Kings",
          "tweet_volume": "37K"
        },
        {
          "name": "Marshawn",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bosa",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "John Schneider",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Myers",
          "tweet_volume": "13K"
        },
        {
          "name": "Lenoir",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Joe Mazzulla",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kenneth Walker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "John Lynch",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pritchard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "184K"
        },
        {
          "name": "Max Christie",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Arepas",
          "tweet_volume": "65K"
        },
        {
          "name": "Viejas",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Amanda Serrano",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "DRAKE THOMAS",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767519331
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Seahawks",
          "tweet_volume": "81K"
        },
        {
          "name": "Jaylen Brown",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Niners",
          "tweet_volume": "14K"
        },
        {
          "name": "Sam Darnold",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Venezuelans",
          "tweet_volume": "949K"
        },
        {
          "name": "#21DaysOfJupiterMobile",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#GoHawks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#FTTB",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#Celtics",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Mike Macdonald",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Shanahan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#Mashle",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "NFC West",
          "tweet_volume": "11K"
        },
        {
          "name": "SDSU",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jason Myers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Panthers",
          "tweet_volume": "57K"
        },
        {
          "name": "Trent",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Kenneth Walker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "John Collins",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "GO ACE",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pearsall",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Fraser Minten",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "John Schneider",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "DRAKE THOMAS",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "1 Seed",
          "tweet_volume": "35K"
        },
        {
          "name": "John Lynch",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Max Christie",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Matthew Schaefer",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Amanda Serrano",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Lenoir",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bucs",
          "tweet_volume": "25K"
        },
        {
          "name": "Jordan Walsh",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Aztecs",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Boogie Fland",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bernie",
          "tweet_volume": "61K"
        },
        {
          "name": "San Diego State",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Braden Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "No Kings",
          "tweet_volume": "35K"
        },
        {
          "name": "Payton Pritchard",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Greenland",
          "tweet_volume": "92K"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "177K"
        },
        {
          "name": "Saleh",
          "tweet_volume": "13K"
        },
        {
          "name": "Intuit Dome",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Ricky",
          "tweet_volume": "23K"
        },
        {
          "name": "Carolina",
          "tweet_volume": "60K"
        },
        {
          "name": "Ty Lue",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jabari",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Arepas",
          "tweet_volume": "52K"
        },
        {
          "name": "Simons",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Haugh",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767509414
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Seahawks",
          "tweet_volume": "62K"
        },
        {
          "name": "Niners",
          "tweet_volume": "12K"
        },
        {
          "name": "Sam Darnold",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#FTTB",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#SEAvsSF",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#GoHawks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Venezuelans",
          "tweet_volume": "879K"
        },
        {
          "name": "Mike Macdonald",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Shanahan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jason Myers",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Panthers",
          "tweet_volume": "55K"
        },
        {
          "name": "Kenneth Walker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "NFC WEST CHAMPS",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "1 SEED",
          "tweet_volume": "30K"
        },
        {
          "name": "Drake Thomas",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bucs",
          "tweet_volume": "24K"
        },
        {
          "name": "John Lynch",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#AEWCollision",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Max Christie",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "John Schneider",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Matthew Schaefer",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Boogie Fland",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Braden Smith",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Trent",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bernie",
          "tweet_volume": "59K"
        },
        {
          "name": "#SerranoTellez",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Saleh",
          "tweet_volume": "13K"
        },
        {
          "name": "NFC South",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Carolina",
          "tweet_volume": "60K"
        },
        {
          "name": "Lenoir",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Jabari",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Charbonnet",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "No Kings",
          "tweet_volume": "32K"
        },
        {
          "name": "Kubiak",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Haugh",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Upton Stout",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Canales",
          "tweet_volume": "15K"
        },
        {
          "name": "Bryce Young",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "VJ Edgecombe",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Brad Allen",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Tatum Bethune",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "The NFC",
          "tweet_volume": "18K"
        },
        {
          "name": "Greenland",
          "tweet_volume": "85K"
        },
        {
          "name": "Fred Warner",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Matos",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cooper Kupp",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Stephanie Han",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Baker",
          "tweet_volume": "22K"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "168K"
        },
        {
          "name": "Todd Golden",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767503369
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Venezuela",
          "tweet_volume": "3.7M"
        },
        {
          "name": "Panthers",
          "tweet_volume": "51K"
        },
        {
          "name": "Panthers",
          "tweet_volume": "51K"
        },
        {
          "name": "Bryce Young",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "NFC South",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Baker",
          "tweet_volume": "22K"
        },
        {
          "name": "#KeepPounding",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#CARvsTB",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Canales",
          "tweet_volume": "14K"
        },
        {
          "name": "Buccaneers",
          "tweet_volume": "18K"
        },
        {
          "name": "Tampa Bay",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Bernie",
          "tweet_volume": "55K"
        },
        {
          "name": "Todd Bowles",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Brad Allen",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#Seahawks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Russia",
          "tweet_volume": "910K"
        },
        {
          "name": "Cuba",
          "tweet_volume": "518K"
        },
        {
          "name": "Coker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#NicolasMaduro",
          "tweet_volume": "106K"
        },
        {
          "name": "TMac",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Pearsall",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cade Otton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Dan Orlovsky",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "#WeAreTheKrewe",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rico Dowdle",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Iraq",
          "tweet_volume": "302K"
        },
        {
          "name": "Putin",
          "tweet_volume": "456K"
        },
        {
          "name": "Greenland",
          "tweet_volume": "73K"
        },
        {
          "name": "Rubio",
          "tweet_volume": "410K"
        },
        {
          "name": "Joan Garcia",
          "tweet_volume": "117K"
        },
        {
          "name": "Mike Evans",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Riddick",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Briefed",
          "tweet_volume": "55K"
        },
        {
          "name": "McMillan",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cam Newton",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "North Korea",
          "tweet_volume": "59K"
        },
        {
          "name": "Go Saints",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Go Falcons",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "No Kings",
          "tweet_volume": "26K"
        },
        {
          "name": "Libya",
          "tweet_volume": "148K"
        },
        {
          "name": "Flea Flicker",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Taiwan",
          "tweet_volume": "230K"
        },
        {
          "name": "Godwin",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Charbonnet",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Evero",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Chavez",
          "tweet_volume": "675K"
        },
        {
          "name": "Trent Williams",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Afghanistan",
          "tweet_volume": "149K"
        },
        {
          "name": "Bin Laden",
          "tweet_volume": "50K"
        },
        {
          "name": "South America",
          "tweet_volume": "58K"
        }
      ],
      "timestamp": 1767493113
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Venezuela",
          "tweet_volume": "3.5M"
        },
        {
          "name": "Venezuela",
          "tweet_volume": "3.5M"
        },
        {
          "name": "FINALLY DID IT",
          "tweet_volume": "1.3M"
        },
        {
          "name": "The PENGU",
          "tweet_volume": "201K"
        },
        {
          "name": "The BONK",
          "tweet_volume": "174K"
        },
        {
          "name": "The Jupiter",
          "tweet_volume": "176K"
        },
        {
          "name": "China",
          "tweet_volume": "739K"
        },
        {
          "name": "The AsterDEX",
          "tweet_volume": "95K"
        },
        {
          "name": "Congress",
          "tweet_volume": "506K"
        },
        {
          "name": "The WET",
          "tweet_volume": "31K"
        },
        {
          "name": "Iraq",
          "tweet_volume": "216K"
        },
        {
          "name": "Cuba",
          "tweet_volume": "359K"
        },
        {
          "name": "Rubio",
          "tweet_volume": "254K"
        },
        {
          "name": "Putin",
          "tweet_volume": "337K"
        },
        {
          "name": "Taiwan",
          "tweet_volume": "178K"
        },
        {
          "name": "The US",
          "tweet_volume": "1.5M"
        },
        {
          "name": "Pope",
          "tweet_volume": "22K"
        },
        {
          "name": "Nike",
          "tweet_volume": "35K"
        },
        {
          "name": "Delcy",
          "tweet_volume": "213K"
        },
        {
          "name": "Nicolás Maduro",
          "tweet_volume": "2M"
        },
        {
          "name": "Monroe Doctrine",
          "tweet_volume": "27K"
        },
        {
          "name": "Declan Rice",
          "tweet_volume": "21K"
        },
        {
          "name": "St. John",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Afghanistan",
          "tweet_volume": "98K"
        },
        {
          "name": "America First",
          "tweet_volume": "118K"
        },
        {
          "name": "Honduras",
          "tweet_volume": "72K"
        },
        {
          "name": "Blue Jays",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Machado",
          "tweet_volume": "341K"
        },
        {
          "name": "Noriega",
          "tweet_volume": "76K"
        },
        {
          "name": "Iran",
          "tweet_volume": "1.3M"
        },
        {
          "name": "#madurocaptured",
          "tweet_volume": "22K"
        },
        {
          "name": "South America",
          "tweet_volume": "38K"
        },
        {
          "name": "Libya",
          "tweet_volume": "81K"
        },
        {
          "name": "Panama",
          "tweet_volume": "79K"
        },
        {
          "name": "Chavez",
          "tweet_volume": "469K"
        },
        {
          "name": "Nobel Peace Prize",
          "tweet_volume": "87K"
        },
        {
          "name": "#BOUARS",
          "tweet_volume": "10K"
        },
        {
          "name": "USS Iwo Jima",
          "tweet_volume": "103K"
        },
        {
          "name": "Bush",
          "tweet_volume": "130K"
        },
        {
          "name": "Greenland",
          "tweet_volume": "39K"
        },
        {
          "name": "Latin America",
          "tweet_volume": "129K"
        },
        {
          "name": "Kentucky",
          "tweet_volume": "21K"
        },
        {
          "name": "Bournemouth",
          "tweet_volume": "56K"
        },
        {
          "name": "Estados Unidos",
          "tweet_volume": "1.4M"
        },
        {
          "name": "#sjubb",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Colombia",
          "tweet_volume": "389K"
        },
        {
          "name": "Noah Williamson",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "EEUU",
          "tweet_volume": "873K"
        },
        {
          "name": "Saddam",
          "tweet_volume": "60K"
        },
        {
          "name": "Dictator",
          "tweet_volume": "428K"
        }
      ],
      "timestamp": 1767472227
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Venezuela",
          "tweet_volume": "3.7M"
        },
        {
          "name": "Venezuela",
          "tweet_volume": "3.7M"
        },
        {
          "name": "China",
          "tweet_volume": "649K"
        },
        {
          "name": "Congress",
          "tweet_volume": "448K"
        },
        {
          "name": "Iraq",
          "tweet_volume": "174K"
        },
        {
          "name": "Rubio",
          "tweet_volume": "174K"
        },
        {
          "name": "Cuba",
          "tweet_volume": "298K"
        },
        {
          "name": "Nicolás Maduro",
          "tweet_volume": "1.9M"
        },
        {
          "name": "Taiwan",
          "tweet_volume": "155K"
        },
        {
          "name": "The US",
          "tweet_volume": "1.4M"
        },
        {
          "name": "#madurocaptured",
          "tweet_volume": "16K"
        },
        {
          "name": "Monroe Doctrine",
          "tweet_volume": "19K"
        },
        {
          "name": "Nike Tech",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Noriega",
          "tweet_volume": "67K"
        },
        {
          "name": "Honduras",
          "tweet_volume": "50K"
        },
        {
          "name": "USS Iwo Jima",
          "tweet_volume": "80K"
        },
        {
          "name": "Panama",
          "tweet_volume": "66K"
        },
        {
          "name": "Iran",
          "tweet_volume": "1.7M"
        },
        {
          "name": "Estados Unidos",
          "tweet_volume": "1.1M"
        },
        {
          "name": "South America",
          "tweet_volume": "30K"
        },
        {
          "name": "Afghanistan",
          "tweet_volume": "75K"
        },
        {
          "name": "Caracas",
          "tweet_volume": "1.2M"
        },
        {
          "name": "Libya",
          "tweet_volume": "62K"
        },
        {
          "name": "Chavez",
          "tweet_volume": "401K"
        },
        {
          "name": "Mark Pope",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "America First",
          "tweet_volume": "100K"
        },
        {
          "name": "Nobel Peace Prize",
          "tweet_volume": "75K"
        },
        {
          "name": "Machado",
          "tweet_volume": "268K"
        },
        {
          "name": "Latin America",
          "tweet_volume": "109K"
        },
        {
          "name": "Delta Force",
          "tweet_volume": "126K"
        },
        {
          "name": "EEUU",
          "tweet_volume": "759K"
        },
        {
          "name": "Colombia",
          "tweet_volume": "343K"
        },
        {
          "name": "Hegseth",
          "tweet_volume": "62K"
        },
        {
          "name": "Bush",
          "tweet_volume": "105K"
        },
        {
          "name": "Madura",
          "tweet_volume": "20K"
        },
        {
          "name": "Massie",
          "tweet_volume": "28K"
        },
        {
          "name": "FAFO",
          "tweet_volume": "87K"
        },
        {
          "name": "Western Hemisphere",
          "tweet_volume": "25K"
        },
        {
          "name": "Bin Laden",
          "tweet_volume": "14K"
        },
        {
          "name": "Cartel",
          "tweet_volume": "305K"
        },
        {
          "name": "Dictator",
          "tweet_volume": "340K"
        },
        {
          "name": "Saddam",
          "tweet_volume": "47K"
        },
        {
          "name": "Delcy",
          "tweet_volume": "160K"
        },
        {
          "name": "Constitution",
          "tweet_volume": "124K"
        },
        {
          "name": "Maduros",
          "tweet_volume": "14K"
        },
        {
          "name": "Venezolanos",
          "tweet_volume": "697K"
        },
        {
          "name": "International",
          "tweet_volume": "495K"
        },
        {
          "name": "SDNY",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Madueke",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Operation Absolute Resolve",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767466653
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Venezuela",
          "tweet_volume": "3.4M"
        },
        {
          "name": "Venezuela",
          "tweet_volume": "3.4M"
        },
        {
          "name": "China",
          "tweet_volume": "601K"
        },
        {
          "name": "Congress",
          "tweet_volume": "420K"
        },
        {
          "name": "Nicolás Maduro",
          "tweet_volume": "1.7M"
        },
        {
          "name": "Cuba",
          "tweet_volume": "267K"
        },
        {
          "name": "Iraq",
          "tweet_volume": "148K"
        },
        {
          "name": "Noriega",
          "tweet_volume": "61K"
        },
        {
          "name": "Taiwan",
          "tweet_volume": "141K"
        },
        {
          "name": "The US",
          "tweet_volume": "1.3M"
        },
        {
          "name": "USS Iwo Jima",
          "tweet_volume": "47K"
        },
        {
          "name": "#madurocaptured",
          "tweet_volume": "12K"
        },
        {
          "name": "Monroe Doctrine",
          "tweet_volume": "15K"
        },
        {
          "name": "Panama",
          "tweet_volume": "58K"
        },
        {
          "name": "Iran",
          "tweet_volume": "1.8M"
        },
        {
          "name": "Caracas",
          "tweet_volume": "1.4M"
        },
        {
          "name": "Estados Unidos",
          "tweet_volume": "1M"
        },
        {
          "name": "Rubio",
          "tweet_volume": "136K"
        },
        {
          "name": "Libya",
          "tweet_volume": "52K"
        },
        {
          "name": "Chavez",
          "tweet_volume": "359K"
        },
        {
          "name": "Delta Force",
          "tweet_volume": "114K"
        },
        {
          "name": "South America",
          "tweet_volume": "26K"
        },
        {
          "name": "Nike Tech",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "EEUU",
          "tweet_volume": "685K"
        },
        {
          "name": "Latin America",
          "tweet_volume": "95K"
        },
        {
          "name": "Nobel Peace Prize",
          "tweet_volume": "68K"
        },
        {
          "name": "Afghanistan",
          "tweet_volume": "62K"
        },
        {
          "name": "SDNY",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Madura",
          "tweet_volume": "19K"
        },
        {
          "name": "FAFO",
          "tweet_volume": "75K"
        },
        {
          "name": "Bin Laden",
          "tweet_volume": "11K"
        },
        {
          "name": "Bush",
          "tweet_volume": "91K"
        },
        {
          "name": "Cartel",
          "tweet_volume": "279K"
        },
        {
          "name": "West Ham",
          "tweet_volume": "24K"
        },
        {
          "name": "Colombia",
          "tweet_volume": "319K"
        },
        {
          "name": "Pete Hegseth",
          "tweet_volume": "24K"
        },
        {
          "name": "Venezolanos",
          "tweet_volume": "603K"
        },
        {
          "name": "Constitution",
          "tweet_volume": "115K"
        },
        {
          "name": "Dictator",
          "tweet_volume": "285K"
        },
        {
          "name": "Saddam",
          "tweet_volume": "38K"
        },
        {
          "name": "Western Hemisphere",
          "tweet_volume": "18K"
        },
        {
          "name": "Cállate",
          "tweet_volume": "45K"
        },
        {
          "name": "Maria Corina Machado",
          "tweet_volume": "187K"
        },
        {
          "name": "Massie",
          "tweet_volume": "24K"
        },
        {
          "name": "Maduros",
          "tweet_volume": "12K"
        },
        {
          "name": "International",
          "tweet_volume": "451K"
        },
        {
          "name": "America First",
          "tweet_volume": "92K"
        },
        {
          "name": "Diosdado",
          "tweet_volume": "196K"
        },
        {
          "name": "Cilia Flores",
          "tweet_volume": "149K"
        },
        {
          "name": "México",
          "tweet_volume": "401K"
        }
      ],
      "timestamp": 1767461067
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Venezuela",
          "tweet_volume": "2.2M"
        },
        {
          "name": "Nicolás Maduro",
          "tweet_volume": "663K"
        },
        {
          "name": "#ZigRecap2025",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Diosdado",
          "tweet_volume": "98K"
        },
        {
          "name": "Cuba",
          "tweet_volume": "155K"
        },
        {
          "name": "Cállate",
          "tweet_volume": "24K"
        },
        {
          "name": "Estados Unidos",
          "tweet_volume": "501K"
        },
        {
          "name": "Noriega",
          "tweet_volume": "23K"
        },
        {
          "name": "Delta Force",
          "tweet_volume": "54K"
        },
        {
          "name": "Delcy",
          "tweet_volume": "62K"
        },
        {
          "name": "EEUU",
          "tweet_volume": "320K"
        },
        {
          "name": "Panama",
          "tweet_volume": "27K"
        },
        {
          "name": "Venezolanos",
          "tweet_volume": "180K"
        },
        {
          "name": "Iraq",
          "tweet_volume": "79K"
        },
        {
          "name": "Iran",
          "tweet_volume": "1.7M"
        },
        {
          "name": "Chavez",
          "tweet_volume": "142K"
        },
        {
          "name": "Good Saturday",
          "tweet_volume": "20K"
        },
        {
          "name": "Monroe Doctrine",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "39K"
        },
        {
          "name": "Narco",
          "tweet_volume": "121K"
        },
        {
          "name": "Padrino",
          "tweet_volume": "71K"
        },
        {
          "name": "Nobel Peace Prize",
          "tweet_volume": "30K"
        },
        {
          "name": "Latin America",
          "tweet_volume": "37K"
        },
        {
          "name": "Marco Rubio",
          "tweet_volume": "43K"
        },
        {
          "name": "Captured",
          "tweet_volume": "226K"
        },
        {
          "name": "Madura",
          "tweet_volume": "10K"
        },
        {
          "name": "The United States",
          "tweet_volume": "447K"
        },
        {
          "name": "#CampRecap2025",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Petro",
          "tweet_volume": "202K"
        },
        {
          "name": "Colombia",
          "tweet_volume": "194K"
        },
        {
          "name": "War Powers Act",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Rusia",
          "tweet_volume": "47K"
        },
        {
          "name": "Mike Lee",
          "tweet_volume": "11K"
        },
        {
          "name": "Russia and China",
          "tweet_volume": "39K"
        },
        {
          "name": "Llora",
          "tweet_volume": "17K"
        },
        {
          "name": "#MeAndTheeSeriesEP8",
          "tweet_volume": "574K"
        },
        {
          "name": "Libya",
          "tweet_volume": "24K"
        },
        {
          "name": "Southern District of New York",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cartel",
          "tweet_volume": "137K"
        },
        {
          "name": "Moscú",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Soles",
          "tweet_volume": "112K"
        },
        {
          "name": "Cállese",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Vete",
          "tweet_volume": "17K"
        },
        {
          "name": "Nicaragua",
          "tweet_volume": "14K"
        },
        {
          "name": "Article II",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Maldito",
          "tweet_volume": "42K"
        },
        {
          "name": "The Sabbath",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Article 2",
          "tweet_volume": "17K"
        },
        {
          "name": "Kidnapped",
          "tweet_volume": "61K"
        },
        {
          "name": "Edmundo González",
          "tweet_volume": "11K"
        }
      ],
      "timestamp": 1767446778
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Venezuela",
          "tweet_volume": "1.5M"
        },
        {
          "name": "#CampRecap2025",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Nicolás Maduro",
          "tweet_volume": "220K"
        },
        {
          "name": "Cállate",
          "tweet_volume": "14K"
        },
        {
          "name": "Cilia",
          "tweet_volume": "20K"
        },
        {
          "name": "Diosdado",
          "tweet_volume": "34K"
        },
        {
          "name": "Estados Unidos",
          "tweet_volume": "238K"
        },
        {
          "name": "Cuba",
          "tweet_volume": "116K"
        },
        {
          "name": "Fuerte Tiuna",
          "tweet_volume": "80K"
        },
        {
          "name": "Delta Force",
          "tweet_volume": "21K"
        },
        {
          "name": "Iraq",
          "tweet_volume": "64K"
        },
        {
          "name": "Captured",
          "tweet_volume": "91K"
        },
        {
          "name": "La Guaira",
          "tweet_volume": "55K"
        },
        {
          "name": "Padrino López",
          "tweet_volume": "29K"
        },
        {
          "name": "Venezolanos",
          "tweet_volume": "69K"
        },
        {
          "name": "Chávez",
          "tweet_volume": "57K"
        },
        {
          "name": "President Maduro",
          "tweet_volume": "69K"
        },
        {
          "name": "Nobel Peace Prize",
          "tweet_volume": "15K"
        },
        {
          "name": "Noriega",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "La Carlota",
          "tweet_volume": "44K"
        },
        {
          "name": "Maldita",
          "tweet_volume": "17K"
        },
        {
          "name": "Chinooks",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Cállese",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Monroe Doctrine",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Petro",
          "tweet_volume": "146K"
        },
        {
          "name": "#URGENTE",
          "tweet_volume": "125K"
        },
        {
          "name": "No New Wars",
          "tweet_volume": "12K"
        },
        {
          "name": "Madura",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Miraflores",
          "tweet_volume": "30K"
        },
        {
          "name": "Panama",
          "tweet_volume": "12K"
        },
        {
          "name": "Delcy Rodríguez",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Russia and China",
          "tweet_volume": "21K"
        },
        {
          "name": "Presidente Trump",
          "tweet_volume": "68K"
        },
        {
          "name": "Peace President",
          "tweet_volume": "46K"
        },
        {
          "name": "Apache",
          "tweet_volume": "22K"
        },
        {
          "name": "China and Russia",
          "tweet_volume": "21K"
        },
        {
          "name": "Cuartel de la Montaña",
          "tweet_volume": "24K"
        },
        {
          "name": "Soles",
          "tweet_volume": "67K"
        },
        {
          "name": "Vete",
          "tweet_volume": "12K"
        },
        {
          "name": "Corre",
          "tweet_volume": "16K"
        },
        {
          "name": "Llora",
          "tweet_volume": "13K"
        },
        {
          "name": "#ULTIMAHORA",
          "tweet_volume": "41K"
        },
        {
          "name": "Reuters",
          "tweet_volume": "70K"
        },
        {
          "name": "160th SOAR",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Fort Tiuna",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "President of Peace",
          "tweet_volume": "21K"
        },
        {
          "name": "Chavista",
          "tweet_volume": "27K"
        },
        {
          "name": "#SmackDown",
          "tweet_volume": "61K"
        },
        {
          "name": "Nicaragua",
          "tweet_volume": "Less than 10k"
        },
        {
          "name": "Sigues",
          "tweet_volume": "Less than 10k"
        }
      ],
      "timestamp": 1767437091
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#SmackDown",
          "tweet_volume": "53K"
        },
        {
          "name": "#DragRace",
          "tweet_volume": "14K"
        },
        {
          "name": "Lebby",
          "tweet_volume": ""
        },
        {
          "name": "Kamario Taylor",
          "tweet_volume": ""
        },
        {
          "name": "#WinterClassic",
          "tweet_volume": ""
        },
        {
          "name": "Wake Forest",
          "tweet_volume": ""
        },
        {
          "name": "Mississippi State",
          "tweet_volume": ""
        },
        {
          "name": "Matt Cardona",
          "tweet_volume": ""
        },
        {
          "name": "Giulia",
          "tweet_volume": ""
        },
        {
          "name": "Mika",
          "tweet_volume": "28K"
        },
        {
          "name": "Grizzlies",
          "tweet_volume": ""
        },
        {
          "name": "Nebraska",
          "tweet_volume": "14K"
        },
        {
          "name": "Rangers",
          "tweet_volume": "32K"
        },
        {
          "name": "Gonzaga",
          "tweet_volume": ""
        },
        {
          "name": "Arizona",
          "tweet_volume": "27K"
        },
        {
          "name": "Izzo",
          "tweet_volume": ""
        },
        {
          "name": "#DukesMayoBowl",
          "tweet_volume": ""
        },
        {
          "name": "Trick Williams",
          "tweet_volume": ""
        },
        {
          "name": "Seattle U",
          "tweet_volume": ""
        },
        {
          "name": "Jake LaRavia",
          "tweet_volume": ""
        },
        {
          "name": "Drew",
          "tweet_volume": "62K"
        },
        {
          "name": "Damian Priest",
          "tweet_volume": ""
        },
        {
          "name": "Jaxson Hayes",
          "tweet_volume": ""
        },
        {
          "name": "Aleister Black",
          "tweet_volume": ""
        },
        {
          "name": "Fred Hoiberg",
          "tweet_volume": ""
        },
        {
          "name": "Pat Spencer",
          "tweet_volume": ""
        },
        {
          "name": "Deacs",
          "tweet_volume": ""
        },
        {
          "name": "Michigan State",
          "tweet_volume": "18K"
        },
        {
          "name": "Zags",
          "tweet_volume": ""
        },
        {
          "name": "Fears",
          "tweet_volume": "15K"
        },
        {
          "name": "Sami",
          "tweet_volume": "22K"
        },
        {
          "name": "Go Big Red",
          "tweet_volume": ""
        },
        {
          "name": "Zack Ryder",
          "tweet_volume": ""
        },
        {
          "name": "Stanford",
          "tweet_volume": ""
        },
        {
          "name": "Holiday Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Noah Fifita",
          "tweet_volume": ""
        },
        {
          "name": "Carson Cooper",
          "tweet_volume": ""
        },
        {
          "name": "Fletch",
          "tweet_volume": ""
        },
        {
          "name": "Robby Ashford",
          "tweet_volume": ""
        },
        {
          "name": "Suggs",
          "tweet_volume": ""
        },
        {
          "name": "Quinn Hughes",
          "tweet_volume": ""
        },
        {
          "name": "Carmelo Hayes",
          "tweet_volume": ""
        },
        {
          "name": "Chelsea Green",
          "tweet_volume": ""
        },
        {
          "name": "Rienk Mast",
          "tweet_volume": ""
        },
        {
          "name": "Zelina",
          "tweet_volume": ""
        },
        {
          "name": "Lamelo",
          "tweet_volume": ""
        },
        {
          "name": "#Dateline",
          "tweet_volume": ""
        },
        {
          "name": "Johnny Gargano",
          "tweet_volume": ""
        },
        {
          "name": "Matas Buzelis",
          "tweet_volume": ""
        },
        {
          "name": "Milan Momcilovic",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767422893
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#SmackDown",
          "tweet_volume": "51K"
        },
        {
          "name": "#WinterClassic",
          "tweet_volume": ""
        },
        {
          "name": "#DragRace",
          "tweet_volume": "12K"
        },
        {
          "name": "Giulia",
          "tweet_volume": ""
        },
        {
          "name": "Mika",
          "tweet_volume": "29K"
        },
        {
          "name": "Matt Cardona",
          "tweet_volume": ""
        },
        {
          "name": "Nebraska",
          "tweet_volume": "14K"
        },
        {
          "name": "Rangers",
          "tweet_volume": "32K"
        },
        {
          "name": "Gonzaga",
          "tweet_volume": ""
        },
        {
          "name": "Kamario Taylor",
          "tweet_volume": ""
        },
        {
          "name": "Wake Forest",
          "tweet_volume": ""
        },
        {
          "name": "Mississippi State",
          "tweet_volume": ""
        },
        {
          "name": "Trick Williams",
          "tweet_volume": ""
        },
        {
          "name": "Seattle U",
          "tweet_volume": ""
        },
        {
          "name": "Jake LaRavia",
          "tweet_volume": ""
        },
        {
          "name": "Izzo",
          "tweet_volume": ""
        },
        {
          "name": "Damian Priest",
          "tweet_volume": ""
        },
        {
          "name": "Arizona",
          "tweet_volume": "27K"
        },
        {
          "name": "Aleister Black",
          "tweet_volume": ""
        },
        {
          "name": "Lebby",
          "tweet_volume": ""
        },
        {
          "name": "Drew",
          "tweet_volume": "62K"
        },
        {
          "name": "#DukesMayoBowl",
          "tweet_volume": ""
        },
        {
          "name": "Michigan State",
          "tweet_volume": "18K"
        },
        {
          "name": "Zags",
          "tweet_volume": ""
        },
        {
          "name": "Fred Hoiberg",
          "tweet_volume": ""
        },
        {
          "name": "Carson Cooper",
          "tweet_volume": ""
        },
        {
          "name": "Fears",
          "tweet_volume": "15K"
        },
        {
          "name": "Sami",
          "tweet_volume": "22K"
        },
        {
          "name": "Go Big Red",
          "tweet_volume": ""
        },
        {
          "name": "Zack Ryder",
          "tweet_volume": ""
        },
        {
          "name": "Jaxson Hayes",
          "tweet_volume": ""
        },
        {
          "name": "Stanford",
          "tweet_volume": ""
        },
        {
          "name": "Holiday Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Pat Spencer",
          "tweet_volume": ""
        },
        {
          "name": "Suggs",
          "tweet_volume": ""
        },
        {
          "name": "Chelsea Green",
          "tweet_volume": ""
        },
        {
          "name": "Rienk Mast",
          "tweet_volume": ""
        },
        {
          "name": "Kit Wilson",
          "tweet_volume": ""
        },
        {
          "name": "Fletch",
          "tweet_volume": ""
        },
        {
          "name": "Robby Ashford",
          "tweet_volume": ""
        },
        {
          "name": "#TimeToHunt",
          "tweet_volume": ""
        },
        {
          "name": "Zelina",
          "tweet_volume": ""
        },
        {
          "name": "Jordynne Grace",
          "tweet_volume": ""
        },
        {
          "name": "Carmelo Hayes",
          "tweet_volume": ""
        },
        {
          "name": "Panarin",
          "tweet_volume": ""
        },
        {
          "name": "Rhea",
          "tweet_volume": "13K"
        },
        {
          "name": "Will Richard",
          "tweet_volume": ""
        },
        {
          "name": "Milan Momcilovic",
          "tweet_volume": ""
        },
        {
          "name": "Kevin Jennings",
          "tweet_volume": ""
        },
        {
          "name": "Huskers",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767417386
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#FanCashDropPromotion",
          "tweet_volume": ""
        },
        {
          "name": "Robertson",
          "tweet_volume": ""
        },
        {
          "name": "Iran",
          "tweet_volume": "1.1M"
        },
        {
          "name": "Dilbert",
          "tweet_volume": ""
        },
        {
          "name": "Trocheck",
          "tweet_volume": ""
        },
        {
          "name": "JT Miller",
          "tweet_volume": ""
        },
        {
          "name": "Good Friday",
          "tweet_volume": "45K"
        },
        {
          "name": "Caufield",
          "tweet_volume": ""
        },
        {
          "name": "Brock Nelson",
          "tweet_volume": ""
        },
        {
          "name": "Team USA",
          "tweet_volume": ""
        },
        {
          "name": "Mamdani",
          "tweet_volume": "563K"
        },
        {
          "name": "#FridayVibes",
          "tweet_volume": ""
        },
        {
          "name": "#OurBestGiftJISOODay",
          "tweet_volume": "91K"
        },
        {
          "name": "Bill Guerin",
          "tweet_volume": ""
        },
        {
          "name": "#언제나_사랑을_주는_지수야_생일축하해",
          "tweet_volume": "88K"
        },
        {
          "name": "#LastFourWatched",
          "tweet_volume": ""
        },
        {
          "name": "Officially in the Portal",
          "tweet_volume": ""
        },
        {
          "name": "Scott",
          "tweet_volume": "154K"
        },
        {
          "name": "DeBrincat",
          "tweet_volume": ""
        },
        {
          "name": "Antonio Pierce",
          "tweet_volume": ""
        },
        {
          "name": "Robo",
          "tweet_volume": "29K"
        },
        {
          "name": "First Friday",
          "tweet_volume": "14K"
        },
        {
          "name": "RED Friday",
          "tweet_volume": ""
        },
        {
          "name": "Friday of 2026",
          "tweet_volume": ""
        },
        {
          "name": "Locked and Loaded",
          "tweet_volume": "42K"
        },
        {
          "name": "Happy Friyay",
          "tweet_volume": ""
        },
        {
          "name": "Shlomo",
          "tweet_volume": "24K"
        },
        {
          "name": "Adam Fox",
          "tweet_volume": ""
        },
        {
          "name": "How to Fail",
          "tweet_volume": ""
        },
        {
          "name": "AI Alert",
          "tweet_volume": "12K"
        },
        {
          "name": "Kiffin",
          "tweet_volume": "34K"
        },
        {
          "name": "Individualism",
          "tweet_volume": "53K"
        },
        {
          "name": "Billy G",
          "tweet_volume": ""
        },
        {
          "name": "Lane",
          "tweet_volume": "66K"
        },
        {
          "name": "Seth Jones",
          "tweet_volume": ""
        },
        {
          "name": "Communism",
          "tweet_volume": "52K"
        },
        {
          "name": "IHRA",
          "tweet_volume": "22K"
        },
        {
          "name": "Grokipedia",
          "tweet_volume": ""
        },
        {
          "name": "First Amendment",
          "tweet_volume": "42K"
        },
        {
          "name": "4 Nations",
          "tweet_volume": ""
        },
        {
          "name": "Collectivism",
          "tweet_volume": "99K"
        },
        {
          "name": "New Yorkers",
          "tweet_volume": "44K"
        },
        {
          "name": "Market Focus",
          "tweet_volume": ""
        },
        {
          "name": "Chambliss",
          "tweet_volume": "30K"
        },
        {
          "name": "Faber",
          "tweet_volume": ""
        },
        {
          "name": "Token Signal",
          "tweet_volume": ""
        },
        {
          "name": "Socialism",
          "tweet_volume": "63K"
        },
        {
          "name": "Islamic Republic",
          "tweet_volume": "136K"
        },
        {
          "name": "Jenard",
          "tweet_volume": ""
        },
        {
          "name": "Tommy Lee Jones",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767372509
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Ole Miss",
          "tweet_volume": "77K"
        },
        {
          "name": "Georgia",
          "tweet_volume": "116K"
        },
        {
          "name": "#PowerForce",
          "tweet_volume": ""
        },
        {
          "name": "Lane Kiffin",
          "tweet_volume": "25K"
        },
        {
          "name": "#PreparationForEntry",
          "tweet_volume": "32K"
        },
        {
          "name": "#SugarBowl",
          "tweet_volume": ""
        },
        {
          "name": "Trinidad Chambliss",
          "tweet_volume": "16K"
        },
        {
          "name": "#BLACKWHALE",
          "tweet_volume": ""
        },
        {
          "name": "Kirby",
          "tweet_volume": "21K"
        },
        {
          "name": "#HottyToddy",
          "tweet_volume": ""
        },
        {
          "name": "Jenard",
          "tweet_volume": ""
        },
        {
          "name": "Pete Golding",
          "tweet_volume": ""
        },
        {
          "name": "AI Alert",
          "tweet_volume": "11K"
        },
        {
          "name": "Market Focus",
          "tweet_volume": ""
        },
        {
          "name": "Bobo",
          "tweet_volume": "25K"
        },
        {
          "name": "Token Signal",
          "tweet_volume": ""
        },
        {
          "name": "Tariq",
          "tweet_volume": ""
        },
        {
          "name": "Gunner",
          "tweet_volume": "14K"
        },
        {
          "name": "Dmac",
          "tweet_volume": ""
        },
        {
          "name": "Mamdani",
          "tweet_volume": "468K"
        },
        {
          "name": "Curvy",
          "tweet_volume": "42K"
        },
        {
          "name": "Kawhi Leonard",
          "tweet_volume": ""
        },
        {
          "name": "AI Summary",
          "tweet_volume": ""
        },
        {
          "name": "Rebs",
          "tweet_volume": ""
        },
        {
          "name": "Wine",
          "tweet_volume": "29K"
        },
        {
          "name": "Dawgs",
          "tweet_volume": ""
        },
        {
          "name": "AI Alpha",
          "tweet_volume": ""
        },
        {
          "name": "Aria",
          "tweet_volume": "24K"
        },
        {
          "name": "Sean McDonough",
          "tweet_volume": ""
        },
        {
          "name": "Branch",
          "tweet_volume": "17K"
        },
        {
          "name": "Oxford",
          "tweet_volume": ""
        },
        {
          "name": "Collectivism",
          "tweet_volume": "67K"
        },
        {
          "name": "Tommy Lee Jones",
          "tweet_volume": ""
        },
        {
          "name": "Kewan Lacy",
          "tweet_volume": ""
        },
        {
          "name": "Barron",
          "tweet_volume": "12K"
        },
        {
          "name": "Kermit",
          "tweet_volume": ""
        },
        {
          "name": "Rugged",
          "tweet_volume": "27K"
        },
        {
          "name": "Islamic Republic",
          "tweet_volume": "108K"
        },
        {
          "name": "SWARM",
          "tweet_volume": ""
        },
        {
          "name": "Fiesta Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Baton Rouge",
          "tweet_volume": ""
        },
        {
          "name": "Athens",
          "tweet_volume": ""
        },
        {
          "name": "Fate",
          "tweet_volume": "87K"
        },
        {
          "name": "Gatorade",
          "tweet_volume": ""
        },
        {
          "name": "#forcefridays",
          "tweet_volume": ""
        },
        {
          "name": "#conformitygate",
          "tweet_volume": "51K"
        },
        {
          "name": "#MegaManDO",
          "tweet_volume": ""
        },
        {
          "name": "#DesignARobotMaster",
          "tweet_volume": ""
        },
        {
          "name": "#GenshinSpecialProgram",
          "tweet_volume": "17K"
        },
        {
          "name": "#GenshinImpact",
          "tweet_volume": "123K"
        }
      ],
      "timestamp": 1767352606
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Ole Miss",
          "tweet_volume": "75K"
        },
        {
          "name": "Georgia",
          "tweet_volume": "113K"
        },
        {
          "name": "#PowerForce",
          "tweet_volume": ""
        },
        {
          "name": "Lane Kiffin",
          "tweet_volume": "25K"
        },
        {
          "name": "Trinidad Chambliss",
          "tweet_volume": "15K"
        },
        {
          "name": "Kirby",
          "tweet_volume": "20K"
        },
        {
          "name": "#SugarBowl",
          "tweet_volume": ""
        },
        {
          "name": "#BLACKWHALE",
          "tweet_volume": ""
        },
        {
          "name": "#HottyToddy",
          "tweet_volume": ""
        },
        {
          "name": "Pete Golding",
          "tweet_volume": ""
        },
        {
          "name": "Indiana",
          "tweet_volume": "124K"
        },
        {
          "name": "Bobo",
          "tweet_volume": "24K"
        },
        {
          "name": "Jenard",
          "tweet_volume": ""
        },
        {
          "name": "Tariq",
          "tweet_volume": ""
        },
        {
          "name": "#GoDawgs",
          "tweet_volume": "11K"
        },
        {
          "name": "Gunner",
          "tweet_volume": "13K"
        },
        {
          "name": "Dmac",
          "tweet_volume": ""
        },
        {
          "name": "Rebs",
          "tweet_volume": ""
        },
        {
          "name": "AI Alert",
          "tweet_volume": "11K"
        },
        {
          "name": "Mamdani",
          "tweet_volume": "446K"
        },
        {
          "name": "Kawhi Leonard",
          "tweet_volume": ""
        },
        {
          "name": "Rainbow Fish",
          "tweet_volume": ""
        },
        {
          "name": "Sandrone",
          "tweet_volume": "13K"
        },
        {
          "name": "Lucas Carneiro",
          "tweet_volume": ""
        },
        {
          "name": "Sean McDonough",
          "tweet_volume": ""
        },
        {
          "name": "Token Signal",
          "tweet_volume": ""
        },
        {
          "name": "Branch",
          "tweet_volume": "17K"
        },
        {
          "name": "Market Focus",
          "tweet_volume": ""
        },
        {
          "name": "Lacy",
          "tweet_volume": ""
        },
        {
          "name": "Joe Judge",
          "tweet_volume": ""
        },
        {
          "name": "Pen Name",
          "tweet_volume": ""
        },
        {
          "name": "Wine",
          "tweet_volume": "28K"
        },
        {
          "name": "Ty Lue",
          "tweet_volume": ""
        },
        {
          "name": "Saban",
          "tweet_volume": "19K"
        },
        {
          "name": "Diamond",
          "tweet_volume": "48K"
        },
        {
          "name": "Ferris State",
          "tweet_volume": ""
        },
        {
          "name": "Oxford",
          "tweet_volume": ""
        },
        {
          "name": "Cody Williams",
          "tweet_volume": ""
        },
        {
          "name": "Tommy Lee Jones",
          "tweet_volume": ""
        },
        {
          "name": "Cignetti",
          "tweet_volume": "23K"
        },
        {
          "name": "Natty",
          "tweet_volume": "17K"
        },
        {
          "name": "National Championship",
          "tweet_volume": "13K"
        },
        {
          "name": "Mintzy",
          "tweet_volume": ""
        },
        {
          "name": "Baton Rouge",
          "tweet_volume": ""
        },
        {
          "name": "DeBoer",
          "tweet_volume": "11K"
        },
        {
          "name": "Internet Girl",
          "tweet_volume": "19K"
        },
        {
          "name": "Curvy",
          "tweet_volume": "39K"
        },
        {
          "name": "AI Summary",
          "tweet_volume": ""
        },
        {
          "name": "Collectivism",
          "tweet_volume": "62K"
        },
        {
          "name": "Mississippi",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767347938
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Ole Miss",
          "tweet_volume": "35K"
        },
        {
          "name": "Trinidad Chambliss",
          "tweet_volume": ""
        },
        {
          "name": "Kirby",
          "tweet_volume": "17K"
        },
        {
          "name": "#SugarBowl",
          "tweet_volume": ""
        },
        {
          "name": "Lane Kiffin",
          "tweet_volume": ""
        },
        {
          "name": "Alabama",
          "tweet_volume": "103K"
        },
        {
          "name": "Gunner Stockton",
          "tweet_volume": ""
        },
        {
          "name": "Indiana",
          "tweet_volume": "112K"
        },
        {
          "name": "#GoDawgs",
          "tweet_volume": "11K"
        },
        {
          "name": "Pete Golding",
          "tweet_volume": ""
        },
        {
          "name": "Bobo",
          "tweet_volume": "23K"
        },
        {
          "name": "Sean McDonough",
          "tweet_volume": ""
        },
        {
          "name": "Branch",
          "tweet_volume": "16K"
        },
        {
          "name": "Joe Judge",
          "tweet_volume": ""
        },
        {
          "name": "#CFPplayoffs",
          "tweet_volume": ""
        },
        {
          "name": "Lacy",
          "tweet_volume": ""
        },
        {
          "name": "#HottyToddy",
          "tweet_volume": ""
        },
        {
          "name": "Saban",
          "tweet_volume": "18K"
        },
        {
          "name": "#GenshinSpecialProgram",
          "tweet_volume": ""
        },
        {
          "name": "Mendoza",
          "tweet_volume": "35K"
        },
        {
          "name": "Facemask",
          "tweet_volume": ""
        },
        {
          "name": "DeBoer",
          "tweet_volume": "10K"
        },
        {
          "name": "Cignetti",
          "tweet_volume": "21K"
        },
        {
          "name": "Frazier",
          "tweet_volume": ""
        },
        {
          "name": "Mamdani",
          "tweet_volume": "419K"
        },
        {
          "name": "Harrison Wallace",
          "tweet_volume": ""
        },
        {
          "name": "Notre Dame",
          "tweet_volume": "27K"
        },
        {
          "name": "Cash Jones",
          "tweet_volume": ""
        },
        {
          "name": "Lucas Carneiro",
          "tweet_volume": ""
        },
        {
          "name": "Tonie Morgan",
          "tweet_volume": ""
        },
        {
          "name": "Everette",
          "tweet_volume": ""
        },
        {
          "name": "Collectivism",
          "tweet_volume": "45K"
        },
        {
          "name": "Rose Bowl",
          "tweet_volume": "44K"
        },
        {
          "name": "Kentucky",
          "tweet_volume": "25K"
        },
        {
          "name": "Stribling",
          "tweet_volume": ""
        },
        {
          "name": "Rebs",
          "tweet_volume": ""
        },
        {
          "name": "Hoosiers",
          "tweet_volume": "23K"
        },
        {
          "name": "Ferris State",
          "tweet_volume": ""
        },
        {
          "name": "The SEC",
          "tweet_volume": "66K"
        },
        {
          "name": "Luke Hasz",
          "tweet_volume": ""
        },
        {
          "name": "Naji Marshall",
          "tweet_volume": ""
        },
        {
          "name": "Trey Wallace",
          "tweet_volume": ""
        },
        {
          "name": "Colbie Young",
          "tweet_volume": ""
        },
        {
          "name": "Ty Simpson",
          "tweet_volume": ""
        },
        {
          "name": "Kyle Anderson",
          "tweet_volume": ""
        },
        {
          "name": "Targeting",
          "tweet_volume": "55K"
        },
        {
          "name": "Norman Powell",
          "tweet_volume": ""
        },
        {
          "name": "Greg McElroy",
          "tweet_volume": ""
        },
        {
          "name": "Tommy Lee Jones",
          "tweet_volume": ""
        },
        {
          "name": "Tide",
          "tweet_volume": "29K"
        }
      ],
      "timestamp": 1767330635
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Ole Miss",
          "tweet_volume": "19K"
        },
        {
          "name": "Alabama",
          "tweet_volume": "94K"
        },
        {
          "name": "Indiana",
          "tweet_volume": "105K"
        },
        {
          "name": "Gunner Stockton",
          "tweet_volume": ""
        },
        {
          "name": "#SugarBowl",
          "tweet_volume": ""
        },
        {
          "name": "Joe Judge",
          "tweet_volume": ""
        },
        {
          "name": "Georgia",
          "tweet_volume": "69K"
        },
        {
          "name": "Saban",
          "tweet_volume": "17K"
        },
        {
          "name": "DeBoer",
          "tweet_volume": ""
        },
        {
          "name": "Mendoza",
          "tweet_volume": "32K"
        },
        {
          "name": "#GoDawgs",
          "tweet_volume": ""
        },
        {
          "name": "Cignetti",
          "tweet_volume": "18K"
        },
        {
          "name": "#RoseBowl",
          "tweet_volume": "11K"
        },
        {
          "name": "Cash Jones",
          "tweet_volume": ""
        },
        {
          "name": "Mamdani",
          "tweet_volume": "378K"
        },
        {
          "name": "Hoosiers",
          "tweet_volume": "21K"
        },
        {
          "name": "Notre Dame",
          "tweet_volume": "28K"
        },
        {
          "name": "Ty Simpson",
          "tweet_volume": ""
        },
        {
          "name": "#iufb",
          "tweet_volume": ""
        },
        {
          "name": "Chambliss",
          "tweet_volume": ""
        },
        {
          "name": "Kentucky",
          "tweet_volume": "22K"
        },
        {
          "name": "Luke Hasz",
          "tweet_volume": ""
        },
        {
          "name": "Oregon",
          "tweet_volume": "62K"
        },
        {
          "name": "Collectivism",
          "tweet_volume": "34K"
        },
        {
          "name": "The SEC",
          "tweet_volume": "62K"
        },
        {
          "name": "Tonie Morgan",
          "tweet_volume": ""
        },
        {
          "name": "Norman Powell",
          "tweet_volume": ""
        },
        {
          "name": "Daylen Everette",
          "tweet_volume": ""
        },
        {
          "name": "Pete Golding",
          "tweet_volume": ""
        },
        {
          "name": "#RollTide",
          "tweet_volume": ""
        },
        {
          "name": "Lucas Carneiro",
          "tweet_volume": ""
        },
        {
          "name": "Lane Kiffin",
          "tweet_volume": ""
        },
        {
          "name": "Tuscaloosa",
          "tweet_volume": ""
        },
        {
          "name": "Texas Tech",
          "tweet_volume": "54K"
        },
        {
          "name": "Targeting",
          "tweet_volume": "52K"
        },
        {
          "name": "Colbie Young",
          "tweet_volume": ""
        },
        {
          "name": "Grubb",
          "tweet_volume": ""
        },
        {
          "name": "Kewan Lacy",
          "tweet_volume": ""
        },
        {
          "name": "Zachariah Branch",
          "tweet_volume": ""
        },
        {
          "name": "Austin Mack",
          "tweet_volume": ""
        },
        {
          "name": "Letang",
          "tweet_volume": ""
        },
        {
          "name": "Dae'Quan Wright",
          "tweet_volume": ""
        },
        {
          "name": "Oklahoma",
          "tweet_volume": "33K"
        },
        {
          "name": "Kirby",
          "tweet_volume": "12K"
        },
        {
          "name": "Nate Frazier",
          "tweet_volume": ""
        },
        {
          "name": "Scott",
          "tweet_volume": "129K"
        },
        {
          "name": "Naji Marshall",
          "tweet_volume": ""
        },
        {
          "name": "ESPN",
          "tweet_volume": "54K"
        },
        {
          "name": "New Yorkers",
          "tweet_volume": "26K"
        },
        {
          "name": "Mike Bobo",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767324734
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year",
          "tweet_volume": "1.8M"
        },
        {
          "name": "Texas Tech",
          "tweet_volume": "13K"
        },
        {
          "name": "David Bailey",
          "tweet_volume": ""
        },
        {
          "name": "#OrangeBowl",
          "tweet_volume": ""
        },
        {
          "name": "Dan Lanning",
          "tweet_volume": ""
        },
        {
          "name": "Dante Moore",
          "tweet_volume": ""
        },
        {
          "name": "Stein",
          "tweet_volume": ""
        },
        {
          "name": "Astros",
          "tweet_volume": ""
        },
        {
          "name": "Imai",
          "tweet_volume": "11K"
        },
        {
          "name": "#RoseParade",
          "tweet_volume": ""
        },
        {
          "name": "Finney",
          "tweet_volume": ""
        },
        {
          "name": "Morton",
          "tweet_volume": ""
        },
        {
          "name": "Lee Hunter",
          "tweet_volume": ""
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "2.3M"
        },
        {
          "name": "#WreckEm",
          "tweet_volume": ""
        },
        {
          "name": "Rose Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Atticus Sappington",
          "tweet_volume": ""
        },
        {
          "name": "Red Raiders",
          "tweet_volume": ""
        },
        {
          "name": "Cashman",
          "tweet_volume": ""
        },
        {
          "name": "Tyrone",
          "tweet_volume": ""
        },
        {
          "name": "Indiana",
          "tweet_volume": "32K"
        },
        {
          "name": "Jack Smith",
          "tweet_volume": "284K"
        },
        {
          "name": "#1of1Day",
          "tweet_volume": ""
        },
        {
          "name": "Chelsea",
          "tweet_volume": "301K"
        },
        {
          "name": "Market Focus",
          "tweet_volume": ""
        },
        {
          "name": "#CFBPlayoff",
          "tweet_volume": "15K"
        },
        {
          "name": "AI Alert",
          "tweet_volume": ""
        },
        {
          "name": "Sadiq",
          "tweet_volume": "36K"
        },
        {
          "name": "Frimpong",
          "tweet_volume": ""
        },
        {
          "name": "Wonder Man",
          "tweet_volume": ""
        },
        {
          "name": "Romello Height",
          "tweet_volume": ""
        },
        {
          "name": "Framber",
          "tweet_volume": ""
        },
        {
          "name": "Starting 2026",
          "tweet_volume": "87K"
        },
        {
          "name": "Maresca",
          "tweet_volume": "281K"
        },
        {
          "name": "Token Signal",
          "tweet_volume": ""
        },
        {
          "name": "Runaway",
          "tweet_volume": ""
        },
        {
          "name": "Mr October",
          "tweet_volume": ""
        },
        {
          "name": "Quran",
          "tweet_volume": "103K"
        },
        {
          "name": "Jed Hoyer",
          "tweet_volume": ""
        },
        {
          "name": "Ricketts",
          "tweet_volume": ""
        },
        {
          "name": "Isaac Brown",
          "tweet_volume": ""
        },
        {
          "name": "Welcome to 2026",
          "tweet_volume": "127K"
        },
        {
          "name": "Mamdani",
          "tweet_volume": "194K"
        },
        {
          "name": "Dickey",
          "tweet_volume": ""
        },
        {
          "name": "Vanilla Ice",
          "tweet_volume": ""
        },
        {
          "name": "Phee",
          "tweet_volume": ""
        },
        {
          "name": "Scott Adams",
          "tweet_volume": ""
        },
        {
          "name": "Duce",
          "tweet_volume": ""
        },
        {
          "name": "Jacob Rodriguez",
          "tweet_volume": ""
        },
        {
          "name": "CONGRATULATIONS RM",
          "tweet_volume": "24K"
        }
      ],
      "timestamp": 1767293105
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year",
          "tweet_volume": "5.6M"
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "3.2M"
        },
        {
          "name": "Chelsea",
          "tweet_volume": "255K"
        },
        {
          "name": "AI Alert",
          "tweet_volume": ""
        },
        {
          "name": "Maresca",
          "tweet_volume": "230K"
        },
        {
          "name": "Market Focus",
          "tweet_volume": ""
        },
        {
          "name": "Welcome to 2026",
          "tweet_volume": "130K"
        },
        {
          "name": "Token Signal",
          "tweet_volume": ""
        },
        {
          "name": "Jack Smith",
          "tweet_volume": "235K"
        },
        {
          "name": "#ThankYouCampingWorld",
          "tweet_volume": ""
        },
        {
          "name": "Mother of God",
          "tweet_volume": ""
        },
        {
          "name": "Crans-Montana",
          "tweet_volume": "28K"
        },
        {
          "name": "Runaway",
          "tweet_volume": ""
        },
        {
          "name": "#thursdayvibes",
          "tweet_volume": ""
        },
        {
          "name": "#HolinessDirective",
          "tweet_volume": "46K"
        },
        {
          "name": "Good Thursday",
          "tweet_volume": ""
        },
        {
          "name": "Solemnity of Mary",
          "tweet_volume": ""
        },
        {
          "name": "Quran",
          "tweet_volume": "98K"
        },
        {
          "name": "Starting 2026",
          "tweet_volume": "88K"
        },
        {
          "name": "AI Alpha",
          "tweet_volume": ""
        },
        {
          "name": "Strasbourg",
          "tweet_volume": "19K"
        },
        {
          "name": "AI Summary",
          "tweet_volume": ""
        },
        {
          "name": "Liam Rosenior",
          "tweet_volume": "13K"
        },
        {
          "name": "#StrangersThings5",
          "tweet_volume": "178K"
        },
        {
          "name": "Tuchel",
          "tweet_volume": "12K"
        },
        {
          "name": "Hello 2026",
          "tweet_volume": "127K"
        },
        {
          "name": "New York City",
          "tweet_volume": "106K"
        },
        {
          "name": "#WreckEm",
          "tweet_volume": ""
        },
        {
          "name": "Zohran Mamdani",
          "tweet_volume": "132K"
        },
        {
          "name": "Amorim",
          "tweet_volume": "41K"
        },
        {
          "name": "Make 2026",
          "tweet_volume": "223K"
        },
        {
          "name": "Truck",
          "tweet_volume": "46K"
        },
        {
          "name": "Feliz Año Nuevo",
          "tweet_volume": "428K"
        },
        {
          "name": "Texas Tech",
          "tweet_volume": ""
        },
        {
          "name": "Orange Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Hopper",
          "tweet_volume": "84K"
        },
        {
          "name": "Kali",
          "tweet_volume": "126K"
        },
        {
          "name": "Real Money",
          "tweet_volume": "22K"
        },
        {
          "name": "Vecna",
          "tweet_volume": "178K"
        },
        {
          "name": "Cheers to 2026",
          "tweet_volume": "54K"
        },
        {
          "name": "New Yorkers",
          "tweet_volume": "11K"
        },
        {
          "name": "Hope 2026",
          "tweet_volume": "356K"
        },
        {
          "name": "Clearlake",
          "tweet_volume": "14K"
        },
        {
          "name": "Start 2026",
          "tweet_volume": "228K"
        },
        {
          "name": "Go Canes",
          "tweet_volume": ""
        },
        {
          "name": "mike wheeler",
          "tweet_volume": "91K"
        },
        {
          "name": "Khamenei",
          "tweet_volume": "62K"
        },
        {
          "name": "Merrick Garland",
          "tweet_volume": ""
        },
        {
          "name": "As 2026",
          "tweet_volume": "463K"
        },
        {
          "name": "Datsun",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767280835
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year",
          "tweet_volume": "2.6M"
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "1.6M"
        },
        {
          "name": "#StrangersThings5",
          "tweet_volume": "146K"
        },
        {
          "name": "Miami",
          "tweet_volume": "148K"
        },
        {
          "name": "Ohio State",
          "tweet_volume": "91K"
        },
        {
          "name": "Welcome to 2026",
          "tweet_volume": "116K"
        },
        {
          "name": "#ThankYouCampingWorld",
          "tweet_volume": ""
        },
        {
          "name": "Market Focus",
          "tweet_volume": ""
        },
        {
          "name": "#HolinessDirective",
          "tweet_volume": "18K"
        },
        {
          "name": "Hello 2026",
          "tweet_volume": "113K"
        },
        {
          "name": "AI Alert",
          "tweet_volume": ""
        },
        {
          "name": "mike wheeler",
          "tweet_volume": "81K"
        },
        {
          "name": "Hopper",
          "tweet_volume": "71K"
        },
        {
          "name": "Feliz Año Nuevo",
          "tweet_volume": "394K"
        },
        {
          "name": "Vecna",
          "tweet_volume": "149K"
        },
        {
          "name": "Ryan Day",
          "tweet_volume": "13K"
        },
        {
          "name": "Here's to 2026",
          "tweet_volume": "165K"
        },
        {
          "name": "#RockinEve",
          "tweet_volume": "37K"
        },
        {
          "name": "Kali",
          "tweet_volume": "114K"
        },
        {
          "name": "Joyce",
          "tweet_volume": "69K"
        },
        {
          "name": "Jack Smith",
          "tweet_volume": "197K"
        },
        {
          "name": "Crans-Montana",
          "tweet_volume": "13K"
        },
        {
          "name": "West Coast",
          "tweet_volume": ""
        },
        {
          "name": "Canes",
          "tweet_volume": "23K"
        },
        {
          "name": "Diana Ross",
          "tweet_volume": ""
        },
        {
          "name": "Starting 2026",
          "tweet_volume": "79K"
        },
        {
          "name": "#WinMarcusTickets",
          "tweet_volume": ""
        },
        {
          "name": "Michael Irvin",
          "tweet_volume": ""
        },
        {
          "name": "The U",
          "tweet_volume": "469K"
        },
        {
          "name": "Goodbye 2025",
          "tweet_volume": "111K"
        },
        {
          "name": "vickie",
          "tweet_volume": "33K"
        },
        {
          "name": "Naito",
          "tweet_volume": ""
        },
        {
          "name": "Cheers to 2026",
          "tweet_volume": "49K"
        },
        {
          "name": "Sayin",
          "tweet_volume": "89K"
        },
        {
          "name": "Duffer Brothers",
          "tweet_volume": "45K"
        },
        {
          "name": "byers",
          "tweet_volume": "154K"
        },
        {
          "name": "Carson Beck",
          "tweet_volume": ""
        },
        {
          "name": "Buckeyes",
          "tweet_volume": "17K"
        },
        {
          "name": "mileven",
          "tweet_volume": "69K"
        },
        {
          "name": "Derek",
          "tweet_volume": "37K"
        },
        {
          "name": "Millie",
          "tweet_volume": "61K"
        },
        {
          "name": "Hope 2026",
          "tweet_volume": "338K"
        },
        {
          "name": "Runaway",
          "tweet_volume": ""
        },
        {
          "name": "Mind Flayer",
          "tweet_volume": "16K"
        },
        {
          "name": "Jamie Campbell Bower",
          "tweet_volume": "32K"
        },
        {
          "name": "Purple Rain",
          "tweet_volume": ""
        },
        {
          "name": "Zohran Mamdani",
          "tweet_volume": "108K"
        },
        {
          "name": "Times Square",
          "tweet_volume": "42K"
        },
        {
          "name": "Jeremiah Smith",
          "tweet_volume": ""
        },
        {
          "name": "Datsun",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767267290
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year",
          "tweet_volume": "2.5M"
        },
        {
          "name": "#StrangersThings5",
          "tweet_volume": "130K"
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "1.5M"
        },
        {
          "name": "Miami",
          "tweet_volume": "146K"
        },
        {
          "name": "Ohio State",
          "tweet_volume": "90K"
        },
        {
          "name": "#ThankYouCampingWorld",
          "tweet_volume": ""
        },
        {
          "name": "Ryan Day",
          "tweet_volume": "13K"
        },
        {
          "name": "Hello 2026",
          "tweet_volume": "107K"
        },
        {
          "name": "Welcome to 2026",
          "tweet_volume": "108K"
        },
        {
          "name": "Feliz Año Nuevo",
          "tweet_volume": "381K"
        },
        {
          "name": "mike wheeler",
          "tweet_volume": "77K"
        },
        {
          "name": "#GoCanes",
          "tweet_volume": "31K"
        },
        {
          "name": "Hopper",
          "tweet_volume": "66K"
        },
        {
          "name": "#RockinEve",
          "tweet_volume": "35K"
        },
        {
          "name": "Here's to 2026",
          "tweet_volume": "157K"
        },
        {
          "name": "Vecna",
          "tweet_volume": "139K"
        },
        {
          "name": "AI Alert",
          "tweet_volume": ""
        },
        {
          "name": "Diana Ross",
          "tweet_volume": ""
        },
        {
          "name": "West Coast",
          "tweet_volume": ""
        },
        {
          "name": "Michael Irvin",
          "tweet_volume": ""
        },
        {
          "name": "Joyce",
          "tweet_volume": "65K"
        },
        {
          "name": "Kali",
          "tweet_volume": "111K"
        },
        {
          "name": "Sayin",
          "tweet_volume": "87K"
        },
        {
          "name": "The U",
          "tweet_volume": "476K"
        },
        {
          "name": "#CNNNYE",
          "tweet_volume": "13K"
        },
        {
          "name": "Carson Beck",
          "tweet_volume": ""
        },
        {
          "name": "Goodbye 2025",
          "tweet_volume": "114K"
        },
        {
          "name": "Jeremiah Smith",
          "tweet_volume": ""
        },
        {
          "name": "Cheers to 2026",
          "tweet_volume": "46K"
        },
        {
          "name": "Buckeyes",
          "tweet_volume": "17K"
        },
        {
          "name": "Duffer Brothers",
          "tweet_volume": "40K"
        },
        {
          "name": "vickie",
          "tweet_volume": "31K"
        },
        {
          "name": "Jack Smith",
          "tweet_volume": "186K"
        },
        {
          "name": "Hope 2026",
          "tweet_volume": "327K"
        },
        {
          "name": "Derek",
          "tweet_volume": "33K"
        },
        {
          "name": "byers",
          "tweet_volume": "143K"
        },
        {
          "name": "Starting 2026",
          "tweet_volume": "76K"
        },
        {
          "name": "Times Square",
          "tweet_volume": "41K"
        },
        {
          "name": "East Coast",
          "tweet_volume": ""
        },
        {
          "name": "Pitbull",
          "tweet_volume": ""
        },
        {
          "name": "mileven",
          "tweet_volume": "64K"
        },
        {
          "name": "Naito",
          "tweet_volume": ""
        },
        {
          "name": "Runaway",
          "tweet_volume": ""
        },
        {
          "name": "Jamie Campbell Bower",
          "tweet_volume": "27K"
        },
        {
          "name": "Anderson Cooper",
          "tweet_volume": ""
        },
        {
          "name": "Andy Cohen",
          "tweet_volume": ""
        },
        {
          "name": "Game of Thrones",
          "tweet_volume": ""
        },
        {
          "name": "2026 Media Thread",
          "tweet_volume": ""
        },
        {
          "name": "Officially 2026",
          "tweet_volume": "57K"
        },
        {
          "name": "Feliz 2026",
          "tweet_volume": "413K"
        }
      ],
      "timestamp": 1767259467
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year",
          "tweet_volume": "2.4M"
        },
        {
          "name": "#StrangerThings5",
          "tweet_volume": "102K"
        },
        {
          "name": "Ohio State",
          "tweet_volume": "45K"
        },
        {
          "name": "Miami",
          "tweet_volume": "85K"
        },
        {
          "name": "Jeremiah Smith",
          "tweet_volume": ""
        },
        {
          "name": "#AEWDynamite",
          "tweet_volume": "18K"
        },
        {
          "name": "Ryan Day",
          "tweet_volume": ""
        },
        {
          "name": "Sayin",
          "tweet_volume": "78K"
        },
        {
          "name": "Carson Beck",
          "tweet_volume": ""
        },
        {
          "name": "Willow",
          "tweet_volume": "16K"
        },
        {
          "name": "#CFBPlayoff",
          "tweet_volume": ""
        },
        {
          "name": "#CottonBowl",
          "tweet_volume": ""
        },
        {
          "name": "#CNNNYE",
          "tweet_volume": ""
        },
        {
          "name": "Fielding",
          "tweet_volume": ""
        },
        {
          "name": "Bain",
          "tweet_volume": ""
        },
        {
          "name": "Michael Irvin",
          "tweet_volume": ""
        },
        {
          "name": "Joyce",
          "tweet_volume": "30K"
        },
        {
          "name": "Hopper",
          "tweet_volume": "32K"
        },
        {
          "name": "Caleb Downs",
          "tweet_volume": ""
        },
        {
          "name": "Jack Smith",
          "tweet_volume": "130K"
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "1.3M"
        },
        {
          "name": "Toney",
          "tweet_volume": ""
        },
        {
          "name": "mileven",
          "tweet_volume": "29K"
        },
        {
          "name": "mike wheeler",
          "tweet_volume": "50K"
        },
        {
          "name": "Purple Rain",
          "tweet_volume": ""
        },
        {
          "name": "vickie",
          "tweet_volume": "16K"
        },
        {
          "name": "Bo Jackson",
          "tweet_volume": ""
        },
        {
          "name": "Duffer Brothers",
          "tweet_volume": "11K"
        },
        {
          "name": "Sabres",
          "tweet_volume": ""
        },
        {
          "name": "Cristobal",
          "tweet_volume": ""
        },
        {
          "name": "Derek",
          "tweet_volume": "18K"
        },
        {
          "name": "The U",
          "tweet_volume": "468K"
        },
        {
          "name": "Arch",
          "tweet_volume": "38K"
        },
        {
          "name": "Anderson Cooper",
          "tweet_volume": ""
        },
        {
          "name": "Kali",
          "tweet_volume": "80K"
        },
        {
          "name": "jamie campbell bower",
          "tweet_volume": ""
        },
        {
          "name": "Andy Cohen",
          "tweet_volume": ""
        },
        {
          "name": "Mesidor",
          "tweet_volume": ""
        },
        {
          "name": "Keionte Scott",
          "tweet_volume": ""
        },
        {
          "name": "Binnington",
          "tweet_volume": ""
        },
        {
          "name": "Hartline",
          "tweet_volume": ""
        },
        {
          "name": "Carter Davis",
          "tweet_volume": ""
        },
        {
          "name": "Underwood",
          "tweet_volume": ""
        },
        {
          "name": "steve harrington",
          "tweet_volume": "23K"
        },
        {
          "name": "Datsun",
          "tweet_volume": ""
        },
        {
          "name": "Bruce Brown",
          "tweet_volume": ""
        },
        {
          "name": "Dawson",
          "tweet_volume": ""
        },
        {
          "name": "Shelton",
          "tweet_volume": ""
        },
        {
          "name": "Pick 6",
          "tweet_volume": ""
        },
        {
          "name": "TBS Champion",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767242218
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year",
          "tweet_volume": "1.7M"
        },
        {
          "name": "Happy NYE",
          "tweet_volume": "18K"
        },
        {
          "name": "Iowa",
          "tweet_volume": "28K"
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "712K"
        },
        {
          "name": "#CTWCountdown2026XFreenBecky",
          "tweet_volume": "667K"
        },
        {
          "name": "Vandy",
          "tweet_volume": ""
        },
        {
          "name": "SAROCHA REBECCA X CTW BYE2025",
          "tweet_volume": "656K"
        },
        {
          "name": "Vanderbilt",
          "tweet_volume": ""
        },
        {
          "name": "#RUNWBTSin2026",
          "tweet_volume": "15K"
        },
        {
          "name": "Feliz Año Nuevo",
          "tweet_volume": "72K"
        },
        {
          "name": "#NXXT",
          "tweet_volume": ""
        },
        {
          "name": "As 2025",
          "tweet_volume": "291K"
        },
        {
          "name": "Here's to 2026",
          "tweet_volume": "54K"
        },
        {
          "name": "ReliaQuest Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Gene Deckerhoff",
          "tweet_volume": ""
        },
        {
          "name": "#BTScomeback2026",
          "tweet_volume": "51K"
        },
        {
          "name": "Feliz 2026",
          "tweet_volume": "78K"
        },
        {
          "name": "Goodbye 2025",
          "tweet_volume": "68K"
        },
        {
          "name": "Team Canada",
          "tweet_volume": ""
        },
        {
          "name": "#GoCanes",
          "tweet_volume": ""
        },
        {
          "name": "Cheers to 2026",
          "tweet_volume": "14K"
        },
        {
          "name": "Hope 2026",
          "tweet_volume": "117K"
        },
        {
          "name": "Hearings",
          "tweet_volume": ""
        },
        {
          "name": "Tanner McKee",
          "tweet_volume": ""
        },
        {
          "name": "HAPPY BTS YEAR",
          "tweet_volume": "107K"
        },
        {
          "name": "Hobbes",
          "tweet_volume": ""
        },
        {
          "name": "Mark Gronowski",
          "tweet_volume": ""
        },
        {
          "name": "BANGTAN",
          "tweet_volume": "41K"
        },
        {
          "name": "Good Wednesday",
          "tweet_volume": "20K"
        },
        {
          "name": "NextNRG Inc.",
          "tweet_volume": ""
        },
        {
          "name": "Duke -3",
          "tweet_volume": "20K"
        },
        {
          "name": "Times Square",
          "tweet_volume": "12K"
        },
        {
          "name": "Last Day of 2025",
          "tweet_volume": "117K"
        },
        {
          "name": "Gerard Butler",
          "tweet_volume": ""
        },
        {
          "name": "Buckeyes",
          "tweet_volume": ""
        },
        {
          "name": "Hello 2026",
          "tweet_volume": "52K"
        },
        {
          "name": "NEW TOUR",
          "tweet_volume": "31K"
        },
        {
          "name": "CTW COUNTDOWN WITH ZEE NUNEW",
          "tweet_volume": "381K"
        },
        {
          "name": "BTS YEAR 2026",
          "tweet_volume": "151K"
        },
        {
          "name": "ALWAYS BY WINTER SIDE",
          "tweet_volume": "37K"
        },
        {
          "name": "BTS IS COMING",
          "tweet_volume": "138K"
        },
        {
          "name": "Harada",
          "tweet_volume": ""
        },
        {
          "name": "Tom Wilson",
          "tweet_volume": ""
        },
        {
          "name": "Barmore",
          "tweet_volume": ""
        },
        {
          "name": "Vogue",
          "tweet_volume": "30K"
        },
        {
          "name": "NYE Countdown With SB19",
          "tweet_volume": "55K"
        },
        {
          "name": "Roberto Clemente",
          "tweet_volume": ""
        },
        {
          "name": "Curt Cignetti",
          "tweet_volume": ""
        },
        {
          "name": "Magallanes",
          "tweet_volume": ""
        },
        {
          "name": "Hump Day",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767202081
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Happy New Year's Eve",
          "tweet_volume": "34K"
        },
        {
          "name": "Happy NYE",
          "tweet_volume": ""
        },
        {
          "name": "Good Wednesday",
          "tweet_volume": "15K"
        },
        {
          "name": "Happy 2026",
          "tweet_volume": "224K"
        },
        {
          "name": "OutKast",
          "tweet_volume": ""
        },
        {
          "name": "Whale - Buy",
          "tweet_volume": ""
        },
        {
          "name": "#wednesdaymotivation",
          "tweet_volume": ""
        },
        {
          "name": "#TAXSTRIKE",
          "tweet_volume": ""
        },
        {
          "name": "Feliz Año Nuevo",
          "tweet_volume": "39K"
        },
        {
          "name": "annabeth",
          "tweet_volume": "20K"
        },
        {
          "name": "Goodbye 2025",
          "tweet_volume": "43K"
        },
        {
          "name": "Hello 2026",
          "tweet_volume": "24K"
        },
        {
          "name": "ICONSIAM",
          "tweet_volume": "4.2M"
        },
        {
          "name": "ICONSIAM",
          "tweet_volume": "4.2M"
        },
        {
          "name": "Percy",
          "tweet_volume": "24K"
        },
        {
          "name": "NextNRG Inc.",
          "tweet_volume": ""
        },
        {
          "name": "Lincoln Riley",
          "tweet_volume": ""
        },
        {
          "name": "10m TXs",
          "tweet_volume": ""
        },
        {
          "name": "#RIZIN",
          "tweet_volume": "26K"
        },
        {
          "name": "Chainers",
          "tweet_volume": ""
        },
        {
          "name": "5m TXs",
          "tweet_volume": ""
        },
        {
          "name": "As 2025",
          "tweet_volume": "262K"
        },
        {
          "name": "#GoBucks",
          "tweet_volume": ""
        },
        {
          "name": "The 4D",
          "tweet_volume": "245K"
        },
        {
          "name": "hyuna",
          "tweet_volume": ""
        },
        {
          "name": "Feliz 2026",
          "tweet_volume": "45K"
        },
        {
          "name": "Peter Obi",
          "tweet_volume": "42K"
        },
        {
          "name": "Cheers to 2026",
          "tweet_volume": ""
        },
        {
          "name": "Hope 2026",
          "tweet_volume": "72K"
        },
        {
          "name": "Clipse",
          "tweet_volume": ""
        },
        {
          "name": "Warren Buffett",
          "tweet_volume": ""
        },
        {
          "name": "Pistons",
          "tweet_volume": "10K"
        },
        {
          "name": "QUICK TRADE",
          "tweet_volume": ""
        },
        {
          "name": "Smart Money - Buy",
          "tweet_volume": ""
        },
        {
          "name": "Times Square",
          "tweet_volume": ""
        },
        {
          "name": "Here's to 2026",
          "tweet_volume": "32K"
        },
        {
          "name": "Bangkok",
          "tweet_volume": "137K"
        },
        {
          "name": "FDV 5min",
          "tweet_volume": ""
        },
        {
          "name": "FDV Surge Alert",
          "tweet_volume": ""
        },
        {
          "name": "Generator",
          "tweet_volume": "11K"
        },
        {
          "name": "SAVE Act",
          "tweet_volume": "43K"
        },
        {
          "name": "Alamo Bowl",
          "tweet_volume": ""
        },
        {
          "name": "FDV Alert",
          "tweet_volume": ""
        },
        {
          "name": "Inbreeding",
          "tweet_volume": ""
        },
        {
          "name": "John Denver",
          "tweet_volume": ""
        },
        {
          "name": "The Lakers",
          "tweet_volume": "19K"
        },
        {
          "name": "Trojans",
          "tweet_volume": ""
        },
        {
          "name": "Ayton",
          "tweet_volume": ""
        },
        {
          "name": "Rodman",
          "tweet_volume": ""
        },
        {
          "name": "Isiah Whitlock Jr.",
          "tweet_volume": "47K"
        }
      ],
      "timestamp": 1767189230
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Lakers",
          "tweet_volume": "40K"
        },
        {
          "name": "Lincoln Riley",
          "tweet_volume": ""
        },
        {
          "name": "Pistons",
          "tweet_volume": ""
        },
        {
          "name": "Happy New Year",
          "tweet_volume": "392K"
        },
        {
          "name": "#AlamoBowl",
          "tweet_volume": ""
        },
        {
          "name": "Sasser",
          "tweet_volume": ""
        },
        {
          "name": "Ayton",
          "tweet_volume": ""
        },
        {
          "name": "Jeremy Payne",
          "tweet_volume": ""
        },
        {
          "name": "#taxstrike",
          "tweet_volume": ""
        },
        {
          "name": "#LakeShow",
          "tweet_volume": ""
        },
        {
          "name": "Maiava",
          "tweet_volume": ""
        },
        {
          "name": "#RIZIN",
          "tweet_volume": "13K"
        },
        {
          "name": "Tennessee",
          "tweet_volume": "33K"
        },
        {
          "name": "Ken Seals",
          "tweet_volume": ""
        },
        {
          "name": "Duncan Robinson",
          "tweet_volume": ""
        },
        {
          "name": "Luka and LeBron",
          "tweet_volume": ""
        },
        {
          "name": "Ron Holland",
          "tweet_volume": ""
        },
        {
          "name": "#FightOn",
          "tweet_volume": ""
        },
        {
          "name": "Reggie Miller",
          "tweet_volume": ""
        },
        {
          "name": "JJ Redick",
          "tweet_volume": ""
        },
        {
          "name": "Chainers",
          "tweet_volume": ""
        },
        {
          "name": "Pelinka",
          "tweet_volume": ""
        },
        {
          "name": "Cade",
          "tweet_volume": "25K"
        },
        {
          "name": "Laravia",
          "tweet_volume": ""
        },
        {
          "name": "LINGORM COUNTDOWN ICONSIAM",
          "tweet_volume": "1.1M"
        },
        {
          "name": "VJ Edgecombe",
          "tweet_volume": ""
        },
        {
          "name": "The SEC",
          "tweet_volume": "37K"
        },
        {
          "name": "OutKast",
          "tweet_volume": ""
        },
        {
          "name": "Trojans",
          "tweet_volume": ""
        },
        {
          "name": "Jaden Richardson",
          "tweet_volume": ""
        },
        {
          "name": "Big 10",
          "tweet_volume": ""
        },
        {
          "name": "grover",
          "tweet_volume": ""
        },
        {
          "name": "Ja Morant",
          "tweet_volume": ""
        },
        {
          "name": "Keyonte George",
          "tweet_volume": ""
        },
        {
          "name": "Derrick White",
          "tweet_volume": ""
        },
        {
          "name": "LeBron and Luka",
          "tweet_volume": ""
        },
        {
          "name": "Bangkok",
          "tweet_volume": "116K"
        },
        {
          "name": "Embiid",
          "tweet_volume": ""
        },
        {
          "name": "Sixers",
          "tweet_volume": ""
        },
        {
          "name": "Grizzlies",
          "tweet_volume": ""
        },
        {
          "name": "Adou",
          "tweet_volume": ""
        },
        {
          "name": "The 4D",
          "tweet_volume": "208K"
        },
        {
          "name": "Marcus Smart",
          "tweet_volume": ""
        },
        {
          "name": "Longstreet",
          "tweet_volume": ""
        },
        {
          "name": "Clay Helton",
          "tweet_volume": ""
        },
        {
          "name": "Duren",
          "tweet_volume": ""
        },
        {
          "name": "Whale - Buy",
          "tweet_volume": ""
        },
        {
          "name": "Kleber",
          "tweet_volume": ""
        },
        {
          "name": "Big Ten",
          "tweet_volume": ""
        },
        {
          "name": "Dalton Knecht",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767172811
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Tennessee",
          "tweet_volume": "26K"
        },
        {
          "name": "#WWENXT",
          "tweet_volume": "10K"
        },
        {
          "name": "Heupel",
          "tweet_volume": ""
        },
        {
          "name": "Happy New Year",
          "tweet_volume": "261K"
        },
        {
          "name": "Caleb Wilson",
          "tweet_volume": ""
        },
        {
          "name": "#RHOSLC",
          "tweet_volume": ""
        },
        {
          "name": "Cedric Coward",
          "tweet_volume": ""
        },
        {
          "name": "Embiid",
          "tweet_volume": ""
        },
        {
          "name": "The SEC",
          "tweet_volume": "33K"
        },
        {
          "name": "Keyonte George",
          "tweet_volume": ""
        },
        {
          "name": "Maxey",
          "tweet_volume": ""
        },
        {
          "name": "Bill Kennedy",
          "tweet_volume": ""
        },
        {
          "name": "#MusicCityBowl",
          "tweet_volume": ""
        },
        {
          "name": "#Illini",
          "tweet_volume": ""
        },
        {
          "name": "Grizzlies",
          "tweet_volume": ""
        },
        {
          "name": "#NJDevils",
          "tweet_volume": ""
        },
        {
          "name": "The Wire",
          "tweet_volume": "20K"
        },
        {
          "name": "Max Gilbert",
          "tweet_volume": ""
        },
        {
          "name": "Jaren Jackson",
          "tweet_volume": ""
        },
        {
          "name": "Marquette",
          "tweet_volume": ""
        },
        {
          "name": "Seton Hall",
          "tweet_volume": ""
        },
        {
          "name": "Paul George",
          "tweet_volume": ""
        },
        {
          "name": "Clay Davis",
          "tweet_volume": ""
        },
        {
          "name": "Luke Altmyer",
          "tweet_volume": ""
        },
        {
          "name": "Tarasov",
          "tweet_volume": ""
        },
        {
          "name": "Big Ten",
          "tweet_volume": ""
        },
        {
          "name": "Ja Morant",
          "tweet_volume": ""
        },
        {
          "name": "VJ Edgecombe",
          "tweet_volume": ""
        },
        {
          "name": "King Miller",
          "tweet_volume": ""
        },
        {
          "name": "Derrick White",
          "tweet_volume": ""
        },
        {
          "name": "Ken Seals",
          "tweet_volume": ""
        },
        {
          "name": "Gen X",
          "tweet_volume": "11K"
        },
        {
          "name": "Isiah Whitlock Jr.",
          "tweet_volume": "28K"
        },
        {
          "name": "Diggs",
          "tweet_volume": "69K"
        },
        {
          "name": "Freddie",
          "tweet_volume": ""
        },
        {
          "name": "Maiava",
          "tweet_volume": ""
        },
        {
          "name": "Britani",
          "tweet_volume": ""
        },
        {
          "name": "Fallon",
          "tweet_volume": ""
        },
        {
          "name": "Another SEC",
          "tweet_volume": ""
        },
        {
          "name": "Alamo Bowl",
          "tweet_volume": ""
        },
        {
          "name": "Tatiana",
          "tweet_volume": "28K"
        },
        {
          "name": "Doechii",
          "tweet_volume": "24K"
        },
        {
          "name": "Generator",
          "tweet_volume": ""
        },
        {
          "name": "Fitz",
          "tweet_volume": ""
        },
        {
          "name": "Keefe",
          "tweet_volume": ""
        },
        {
          "name": "Nick Lardis",
          "tweet_volume": ""
        },
        {
          "name": "Meredith",
          "tweet_volume": ""
        },
        {
          "name": "Joakim Dodson",
          "tweet_volume": ""
        },
        {
          "name": "IT JUST MEANS MORE",
          "tweet_volume": ""
        },
        {
          "name": "Booker T",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767152883
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Diggs",
          "tweet_volume": "53K"
        },
        {
          "name": "Max Gilbert",
          "tweet_volume": ""
        },
        {
          "name": "Clay Davis",
          "tweet_volume": ""
        },
        {
          "name": "Arsenal",
          "tweet_volume": "310K"
        },
        {
          "name": "Amorim",
          "tweet_volume": "58K"
        },
        {
          "name": "#DinoMemeContest",
          "tweet_volume": ""
        },
        {
          "name": "The Wire",
          "tweet_volume": "16K"
        },
        {
          "name": "Tennessee",
          "tweet_volume": "17K"
        },
        {
          "name": "Happy New Year",
          "tweet_volume": "214K"
        },
        {
          "name": "Isiah Whitlock Jr.",
          "tweet_volume": ""
        },
        {
          "name": "Tatiana Schlossberg",
          "tweet_volume": "14K"
        },
        {
          "name": "Doechii",
          "tweet_volume": "14K"
        },
        {
          "name": "Wolves",
          "tweet_volume": "83K"
        },
        {
          "name": "#ARSAVL",
          "tweet_volume": "18K"
        },
        {
          "name": "Villa",
          "tweet_volume": "166K"
        },
        {
          "name": "#COYG",
          "tweet_volume": ""
        },
        {
          "name": "Merino",
          "tweet_volume": "20K"
        },
        {
          "name": "Kardi",
          "tweet_volume": ""
        },
        {
          "name": "Generator",
          "tweet_volume": ""
        },
        {
          "name": "Odegaard",
          "tweet_volume": "22K"
        },
        {
          "name": "#Illini",
          "tweet_volume": ""
        },
        {
          "name": "Arteta",
          "tweet_volume": "36K"
        },
        {
          "name": "Raya",
          "tweet_volume": "24K"
        },
        {
          "name": "Gabriel Jesus",
          "tweet_volume": "26K"
        },
        {
          "name": "Joey Aguilar",
          "tweet_volume": ""
        },
        {
          "name": "Emery",
          "tweet_volume": "35K"
        },
        {
          "name": "#MusicCityBowl",
          "tweet_volume": ""
        },
        {
          "name": "Cunha",
          "tweet_volume": "20K"
        },
        {
          "name": "Estevao",
          "tweet_volume": "25K"
        },
        {
          "name": "LA Tech",
          "tweet_volume": ""
        },
        {
          "name": "Richard Fowler",
          "tweet_volume": ""
        },
        {
          "name": "New Year's Eve",
          "tweet_volume": "87K"
        },
        {
          "name": "Clooney",
          "tweet_volume": "19K"
        },
        {
          "name": "Coastal Carolina",
          "tweet_volume": ""
        },
        {
          "name": "Manchester United",
          "tweet_volume": "49K"
        },
        {
          "name": "Trossard",
          "tweet_volume": "29K"
        },
        {
          "name": "Chelsea",
          "tweet_volume": "118K"
        },
        {
          "name": "Zirkzee",
          "tweet_volume": "15K"
        },
        {
          "name": "Richard Smallwood",
          "tweet_volume": ""
        },
        {
          "name": "Maresca",
          "tweet_volume": "23K"
        },
        {
          "name": "Martinez",
          "tweet_volume": "34K"
        },
        {
          "name": "Onana",
          "tweet_volume": "10K"
        },
        {
          "name": "Big Gabi",
          "tweet_volume": ""
        },
        {
          "name": "Louisiana Tech",
          "tweet_volume": ""
        },
        {
          "name": "MICHAEL CLIFFORD",
          "tweet_volume": ""
        },
        {
          "name": "Lammens",
          "tweet_volume": ""
        },
        {
          "name": "Sesko",
          "tweet_volume": "14K"
        },
        {
          "name": "Caroline Kennedy",
          "tweet_volume": ""
        },
        {
          "name": "Luke Altmyer",
          "tweet_volume": ""
        },
        {
          "name": "Bournemouth",
          "tweet_volume": "60K"
        }
      ],
      "timestamp": 1767141716
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "#DinoMemeContest",
          "tweet_volume": ""
        },
        {
          "name": "$CAMP",
          "tweet_volume": ""
        },
        {
          "name": "The AsterDEX",
          "tweet_volume": "84K"
        },
        {
          "name": "Diggs",
          "tweet_volume": "43K"
        },
        {
          "name": "Arsenal",
          "tweet_volume": "199K"
        },
        {
          "name": "Amorim",
          "tweet_volume": "29K"
        },
        {
          "name": "#ARSAVL",
          "tweet_volume": "11K"
        },
        {
          "name": "Merino",
          "tweet_volume": "17K"
        },
        {
          "name": "Tatiana Schlossberg",
          "tweet_volume": "10K"
        },
        {
          "name": "Estevao",
          "tweet_volume": "20K"
        },
        {
          "name": "Villa",
          "tweet_volume": "119K"
        },
        {
          "name": "Odegaard",
          "tweet_volume": "14K"
        },
        {
          "name": "#COYG",
          "tweet_volume": ""
        },
        {
          "name": "Doechii",
          "tweet_volume": ""
        },
        {
          "name": "Gabriel Jesus",
          "tweet_volume": ""
        },
        {
          "name": "Raya",
          "tweet_volume": "20K"
        },
        {
          "name": "Happy New Year",
          "tweet_volume": "197K"
        },
        {
          "name": "Cunha",
          "tweet_volume": "13K"
        },
        {
          "name": "#MUFC",
          "tweet_volume": "17K"
        },
        {
          "name": "Lammens",
          "tweet_volume": ""
        },
        {
          "name": "FINALLY DID IT",
          "tweet_volume": "827K"
        },
        {
          "name": "#MUNWOL",
          "tweet_volume": ""
        },
        {
          "name": "Generator",
          "tweet_volume": ""
        },
        {
          "name": "Onana",
          "tweet_volume": ""
        },
        {
          "name": "Trossard",
          "tweet_volume": "11K"
        },
        {
          "name": "Martinez",
          "tweet_volume": "25K"
        },
        {
          "name": "Richard Smallwood",
          "tweet_volume": ""
        },
        {
          "name": "Big Gabi",
          "tweet_volume": ""
        },
        {
          "name": "Arteta",
          "tweet_volume": "18K"
        },
        {
          "name": "Caicedo",
          "tweet_volume": "12K"
        },
        {
          "name": "Sesko",
          "tweet_volume": ""
        },
        {
          "name": "Delap",
          "tweet_volume": "12K"
        },
        {
          "name": "Saka",
          "tweet_volume": "31K"
        },
        {
          "name": "Louisiana Tech",
          "tweet_volume": ""
        },
        {
          "name": "Zirkzee",
          "tweet_volume": "11K"
        },
        {
          "name": "Gyokeres",
          "tweet_volume": "16K"
        },
        {
          "name": "Maresca",
          "tweet_volume": "18K"
        },
        {
          "name": "Bournemouth",
          "tweet_volume": "53K"
        },
        {
          "name": "Enzo",
          "tweet_volume": "23K"
        },
        {
          "name": "Ayden Heaven",
          "tweet_volume": ""
        },
        {
          "name": "LA Tech",
          "tweet_volume": ""
        },
        {
          "name": "George Clooney",
          "tweet_volume": "13K"
        },
        {
          "name": "Rendon",
          "tweet_volume": ""
        },
        {
          "name": "Hincapie",
          "tweet_volume": ""
        },
        {
          "name": "Chalobah",
          "tweet_volume": ""
        },
        {
          "name": "Garnacho",
          "tweet_volume": "16K"
        },
        {
          "name": "Coastal Carolina",
          "tweet_volume": ""
        },
        {
          "name": "Watkins",
          "tweet_volume": "10K"
        },
        {
          "name": "Angels",
          "tweet_volume": "24K"
        },
        {
          "name": "$CITR",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767133150
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "FINALLY DID IT",
          "tweet_volume": "836K"
        },
        {
          "name": "The PENGU",
          "tweet_volume": "242K"
        },
        {
          "name": "The Jupiter",
          "tweet_volume": "217K"
        },
        {
          "name": "The BONK",
          "tweet_volume": "144K"
        },
        {
          "name": "Richard Smallwood",
          "tweet_volume": ""
        },
        {
          "name": "Thor",
          "tweet_volume": "49K"
        },
        {
          "name": "#LingOrmHNYatICONSIAM",
          "tweet_volume": "1.1M"
        },
        {
          "name": "Loki",
          "tweet_volume": "23K"
        },
        {
          "name": "Brees",
          "tweet_volume": ""
        },
        {
          "name": "Fred Taylor",
          "tweet_volume": ""
        },
        {
          "name": "Witten",
          "tweet_volume": ""
        },
        {
          "name": "Happy New Year",
          "tweet_volume": "164K"
        },
        {
          "name": "#FanDuelReplay",
          "tweet_volume": ""
        },
        {
          "name": "Gore",
          "tweet_volume": "10K"
        },
        {
          "name": "Kuechly",
          "tweet_volume": ""
        },
        {
          "name": "Fitzgerald",
          "tweet_volume": ""
        },
        {
          "name": "Chao Phraya",
          "tweet_volume": "16K"
        },
        {
          "name": "#tuesdayvibe",
          "tweet_volume": ""
        },
        {
          "name": "Vinatieri",
          "tweet_volume": ""
        },
        {
          "name": "#MrFakeTrump",
          "tweet_volume": ""
        },
        {
          "name": "Chip Kelly",
          "tweet_volume": ""
        },
        {
          "name": "Stefon Diggs",
          "tweet_volume": ""
        },
        {
          "name": "Good Tuesday",
          "tweet_volume": "41K"
        },
        {
          "name": "Suggs",
          "tweet_volume": ""
        },
        {
          "name": "The 4D",
          "tweet_volume": "43K"
        },
        {
          "name": "Willie Anderson",
          "tweet_volume": ""
        },
        {
          "name": "#ScreenPit",
          "tweet_volume": ""
        },
        {
          "name": "Holt",
          "tweet_volume": ""
        },
        {
          "name": "Yanda",
          "tweet_volume": ""
        },
        {
          "name": "NextNRG Inc",
          "tweet_volume": ""
        },
        {
          "name": "Taco Tuesday",
          "tweet_volume": "12K"
        },
        {
          "name": "New Year's Eve",
          "tweet_volume": "57K"
        },
        {
          "name": "Darren Woodson",
          "tweet_volume": ""
        },
        {
          "name": "Gigantic",
          "tweet_volume": "24K"
        },
        {
          "name": "Pro Football Hall of Fame",
          "tweet_volume": ""
        },
        {
          "name": "Eli Manning",
          "tweet_volume": ""
        },
        {
          "name": "Hela",
          "tweet_volume": ""
        },
        {
          "name": "Northwestern",
          "tweet_volume": ""
        },
        {
          "name": "Kevin Williams",
          "tweet_volume": ""
        },
        {
          "name": "Politico",
          "tweet_volume": "108K"
        },
        {
          "name": "Sandy Koufax",
          "tweet_volume": ""
        },
        {
          "name": "Yemen",
          "tweet_volume": "81K"
        },
        {
          "name": "5m TXs",
          "tweet_volume": ""
        },
        {
          "name": "The BULLISH",
          "tweet_volume": "35K"
        },
        {
          "name": "Hines Ward",
          "tweet_volume": ""
        },
        {
          "name": "Rodney Harrison",
          "tweet_volume": ""
        },
        {
          "name": "Bangkok",
          "tweet_volume": "83K"
        },
        {
          "name": "Tuesday of 2025",
          "tweet_volume": "10K"
        },
        {
          "name": "Reggie Wayne",
          "tweet_volume": ""
        },
        {
          "name": "Love and Thunder",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767116980
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Good Tuesday",
          "tweet_volume": "24K"
        },
        {
          "name": "Falcons",
          "tweet_volume": "51K"
        },
        {
          "name": "Whale - Buy",
          "tweet_volume": ""
        },
        {
          "name": "dane",
          "tweet_volume": "16K"
        },
        {
          "name": "#HealingServiceDay1",
          "tweet_volume": "27K"
        },
        {
          "name": "JIANKUI HE",
          "tweet_volume": ""
        },
        {
          "name": "Camp Haven",
          "tweet_volume": "10K"
        },
        {
          "name": "Stafford",
          "tweet_volume": "40K"
        },
        {
          "name": "QUICK TRADE",
          "tweet_volume": ""
        },
        {
          "name": "Smart Money - Buy",
          "tweet_volume": ""
        },
        {
          "name": "quinn",
          "tweet_volume": "47K"
        },
        {
          "name": "#KingRezaPahlavi",
          "tweet_volume": "72K"
        },
        {
          "name": "10m TXs",
          "tweet_volume": ""
        },
        {
          "name": "5m TXs",
          "tweet_volume": ""
        },
        {
          "name": "Puka",
          "tweet_volume": "22K"
        },
        {
          "name": "Bijan",
          "tweet_volume": "33K"
        },
        {
          "name": "$LIT",
          "tweet_volume": "12K"
        },
        {
          "name": "#NewYearsAdviceFromTeyvat",
          "tweet_volume": ""
        },
        {
          "name": "#GenshinMoonInvitation",
          "tweet_volume": ""
        },
        {
          "name": "Yemen",
          "tweet_volume": "59K"
        },
        {
          "name": "FDV 5min",
          "tweet_volume": ""
        },
        {
          "name": "FDV Alert",
          "tweet_volume": ""
        },
        {
          "name": "Hudcon",
          "tweet_volume": "14K"
        },
        {
          "name": "Manus",
          "tweet_volume": "19K"
        },
        {
          "name": "Market Cap Surges",
          "tweet_volume": ""
        },
        {
          "name": "Iranian",
          "tweet_volume": "128K"
        },
        {
          "name": "#MakeOffer",
          "tweet_volume": "21K"
        },
        {
          "name": "Domain For Sale",
          "tweet_volume": "21K"
        },
        {
          "name": "FDV Surge Alert",
          "tweet_volume": ""
        },
        {
          "name": "Atwell",
          "tweet_volume": ""
        },
        {
          "name": "Raheem Morris",
          "tweet_volume": ""
        },
        {
          "name": "Jacksepticeye",
          "tweet_volume": ""
        },
        {
          "name": "McVay",
          "tweet_volume": ""
        },
        {
          "name": "Ye Shunguang",
          "tweet_volume": "13K"
        },
        {
          "name": "Mustard",
          "tweet_volume": ""
        },
        {
          "name": "MACK",
          "tweet_volume": ""
        },
        {
          "name": "Shah",
          "tweet_volume": "119K"
        },
        {
          "name": "DJ Humphries",
          "tweet_volume": ""
        },
        {
          "name": "Usos",
          "tweet_volume": "12K"
        },
        {
          "name": "Penix",
          "tweet_volume": ""
        },
        {
          "name": "Cousins",
          "tweet_volume": "19K"
        },
        {
          "name": "WATTS",
          "tweet_volume": ""
        },
        {
          "name": "Verse",
          "tweet_volume": "51K"
        },
        {
          "name": "Hybe",
          "tweet_volume": "106K"
        },
        {
          "name": "Drake Maye MVP",
          "tweet_volume": "11K"
        },
        {
          "name": "Dragon Lee",
          "tweet_volume": ""
        },
        {
          "name": "Deni",
          "tweet_volume": "10K"
        },
        {
          "name": "The Birds",
          "tweet_volume": "21K"
        },
        {
          "name": "#NewYear2026",
          "tweet_volume": ""
        },
        {
          "name": "Rams",
          "tweet_volume": "57K"
        }
      ],
      "timestamp": 1767096807
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Falcons",
          "tweet_volume": "47K"
        },
        {
          "name": "Rams",
          "tweet_volume": "55K"
        },
        {
          "name": "Stafford",
          "tweet_volume": "38K"
        },
        {
          "name": "Puka",
          "tweet_volume": "21K"
        },
        {
          "name": "Bijan",
          "tweet_volume": "31K"
        },
        {
          "name": "#WWERaw",
          "tweet_volume": "48K"
        },
        {
          "name": "Drake Maye",
          "tweet_volume": "23K"
        },
        {
          "name": "Jared Verse",
          "tweet_volume": ""
        },
        {
          "name": "Xavier Watts",
          "tweet_volume": ""
        },
        {
          "name": "#GenshinMoonInvitation",
          "tweet_volume": ""
        },
        {
          "name": "#NewYearsAdviceFromTeyvat",
          "tweet_volume": ""
        },
        {
          "name": "Raheem",
          "tweet_volume": ""
        },
        {
          "name": "#LARvsATL",
          "tweet_volume": ""
        },
        {
          "name": "Caleb Love",
          "tweet_volume": ""
        },
        {
          "name": "DJ Humphries",
          "tweet_volume": ""
        },
        {
          "name": "McVay",
          "tweet_volume": ""
        },
        {
          "name": "mack",
          "tweet_volume": ""
        },
        {
          "name": "Atwell",
          "tweet_volume": ""
        },
        {
          "name": "#DirtyBirds",
          "tweet_volume": ""
        },
        {
          "name": "Max Christie",
          "tweet_volume": ""
        },
        {
          "name": "Blazers",
          "tweet_volume": ""
        },
        {
          "name": "Kirk Cousins",
          "tweet_volume": ""
        },
        {
          "name": "The Usos",
          "tweet_volume": ""
        },
        {
          "name": "Jordan Poole",
          "tweet_volume": ""
        },
        {
          "name": "NFC South",
          "tweet_volume": ""
        },
        {
          "name": "Naji Marshall",
          "tweet_volume": ""
        },
        {
          "name": "Whale - Buy",
          "tweet_volume": ""
        },
        {
          "name": "QUICK TRADE",
          "tweet_volume": ""
        },
        {
          "name": "Smart Money - Buy",
          "tweet_volume": ""
        },
        {
          "name": "Brandon Williams",
          "tweet_volume": ""
        },
        {
          "name": "Dragon Lee",
          "tweet_volume": ""
        },
        {
          "name": "Manus",
          "tweet_volume": "16K"
        },
        {
          "name": "Ernest Borgnine",
          "tweet_volume": ""
        },
        {
          "name": "Carter Hart",
          "tweet_volume": ""
        },
        {
          "name": "AJ Terrell",
          "tweet_volume": ""
        },
        {
          "name": "Deni",
          "tweet_volume": ""
        },
        {
          "name": "Jacksepticeye",
          "tweet_volume": ""
        },
        {
          "name": "Drake London",
          "tweet_volume": ""
        },
        {
          "name": "Sharks",
          "tweet_volume": ""
        },
        {
          "name": "Penix",
          "tweet_volume": ""
        },
        {
          "name": "Anaheim",
          "tweet_volume": ""
        },
        {
          "name": "10m TXs",
          "tweet_volume": ""
        },
        {
          "name": "The 5th",
          "tweet_volume": "54K"
        },
        {
          "name": "Puca",
          "tweet_volume": ""
        },
        {
          "name": "Saints",
          "tweet_volume": "22K"
        },
        {
          "name": "Kyle Pitts",
          "tweet_volume": ""
        },
        {
          "name": "PJ Washington",
          "tweet_volume": ""
        },
        {
          "name": "Xavier Smith",
          "tweet_volume": ""
        },
        {
          "name": "3 INTs",
          "tweet_volume": ""
        },
        {
          "name": "Yabu",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767083159
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Falcons",
          "tweet_volume": "46K"
        },
        {
          "name": "Rams",
          "tweet_volume": "54K"
        },
        {
          "name": "Stafford",
          "tweet_volume": "38K"
        },
        {
          "name": "Puka",
          "tweet_volume": "20K"
        },
        {
          "name": "Bijan",
          "tweet_volume": "30K"
        },
        {
          "name": "#WWERaw",
          "tweet_volume": "47K"
        },
        {
          "name": "Drake Maye",
          "tweet_volume": "23K"
        },
        {
          "name": "Xavier Watts",
          "tweet_volume": ""
        },
        {
          "name": "Jared Verse",
          "tweet_volume": ""
        },
        {
          "name": "Raheem",
          "tweet_volume": ""
        },
        {
          "name": "DJ Humphries",
          "tweet_volume": ""
        },
        {
          "name": "#LARvsATL",
          "tweet_volume": ""
        },
        {
          "name": "McVay",
          "tweet_volume": ""
        },
        {
          "name": "mack",
          "tweet_volume": ""
        },
        {
          "name": "Caleb Love",
          "tweet_volume": ""
        },
        {
          "name": "#GenshinMoonInvitation",
          "tweet_volume": ""
        },
        {
          "name": "#NewYearsAdviceFromTeyvat",
          "tweet_volume": ""
        },
        {
          "name": "#DirtyBirds",
          "tweet_volume": ""
        },
        {
          "name": "Atwell",
          "tweet_volume": ""
        },
        {
          "name": "Kirk Cousins",
          "tweet_volume": ""
        },
        {
          "name": "Blazers",
          "tweet_volume": ""
        },
        {
          "name": "Max Christie",
          "tweet_volume": ""
        },
        {
          "name": "The Usos",
          "tweet_volume": ""
        },
        {
          "name": "The 5th",
          "tweet_volume": "55K"
        },
        {
          "name": "Zane Gonzalez",
          "tweet_volume": ""
        },
        {
          "name": "Jordan Poole",
          "tweet_volume": ""
        },
        {
          "name": "NFC South",
          "tweet_volume": ""
        },
        {
          "name": "Brandon Williams",
          "tweet_volume": ""
        },
        {
          "name": "Carter Hart",
          "tweet_volume": ""
        },
        {
          "name": "Tutu",
          "tweet_volume": ""
        },
        {
          "name": "Naji Marshall",
          "tweet_volume": ""
        },
        {
          "name": "Drake London",
          "tweet_volume": ""
        },
        {
          "name": "Dragon Lee",
          "tweet_volume": ""
        },
        {
          "name": "Joe Buck",
          "tweet_volume": ""
        },
        {
          "name": "AJ Terrell",
          "tweet_volume": ""
        },
        {
          "name": "Ernest Borgnine",
          "tweet_volume": ""
        },
        {
          "name": "Sharks",
          "tweet_volume": ""
        },
        {
          "name": "Whale - Buy",
          "tweet_volume": ""
        },
        {
          "name": "QUICK TRADE",
          "tweet_volume": ""
        },
        {
          "name": "Smart Money - Buy",
          "tweet_volume": ""
        },
        {
          "name": "Penix",
          "tweet_volume": ""
        },
        {
          "name": "Zac Robinson",
          "tweet_volume": ""
        },
        {
          "name": "Anaheim",
          "tweet_volume": ""
        },
        {
          "name": "Manus",
          "tweet_volume": "15K"
        },
        {
          "name": "Deni",
          "tweet_volume": ""
        },
        {
          "name": "Kyle Pitts",
          "tweet_volume": ""
        },
        {
          "name": "Arthur Blank",
          "tweet_volume": ""
        },
        {
          "name": "Nikki",
          "tweet_volume": "31K"
        },
        {
          "name": "Puca",
          "tweet_volume": ""
        },
        {
          "name": "Saints",
          "tweet_volume": "22K"
        }
      ],
      "timestamp": 1767079380
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Falcons",
          "tweet_volume": "41K"
        },
        {
          "name": "Rams",
          "tweet_volume": "50K"
        },
        {
          "name": "Stafford",
          "tweet_volume": "34K"
        },
        {
          "name": "Puka",
          "tweet_volume": "18K"
        },
        {
          "name": "Bijan",
          "tweet_volume": "26K"
        },
        {
          "name": "#WWERaw",
          "tweet_volume": "43K"
        },
        {
          "name": "Xavier Watts",
          "tweet_volume": ""
        },
        {
          "name": "Drake Maye",
          "tweet_volume": "21K"
        },
        {
          "name": "Jared Verse",
          "tweet_volume": ""
        },
        {
          "name": "Raheem Morris",
          "tweet_volume": ""
        },
        {
          "name": "DJ Humphries",
          "tweet_volume": ""
        },
        {
          "name": "#LARvsATL",
          "tweet_volume": ""
        },
        {
          "name": "McVay",
          "tweet_volume": ""
        },
        {
          "name": "Kirk Cousins",
          "tweet_volume": ""
        },
        {
          "name": "#DirtyBirds",
          "tweet_volume": ""
        },
        {
          "name": "Jordan Poole",
          "tweet_volume": ""
        },
        {
          "name": "#RiseUp",
          "tweet_volume": ""
        },
        {
          "name": "Atwell",
          "tweet_volume": ""
        },
        {
          "name": "The Usos",
          "tweet_volume": ""
        },
        {
          "name": "Zane Gonzalez",
          "tweet_volume": ""
        },
        {
          "name": "NFC South",
          "tweet_volume": ""
        },
        {
          "name": "The 5th",
          "tweet_volume": "55K"
        },
        {
          "name": "#GenshinMoonInvitation",
          "tweet_volume": ""
        },
        {
          "name": "Dragon Lee",
          "tweet_volume": ""
        },
        {
          "name": "Carter Hart",
          "tweet_volume": ""
        },
        {
          "name": "Drake London",
          "tweet_volume": ""
        },
        {
          "name": "AJ Terrell",
          "tweet_volume": ""
        },
        {
          "name": "Austin Theory",
          "tweet_volume": ""
        },
        {
          "name": "Joe Buck",
          "tweet_volume": ""
        },
        {
          "name": "Nikki",
          "tweet_volume": "31K"
        },
        {
          "name": "Kyle Pitts",
          "tweet_volume": ""
        },
        {
          "name": "Penix",
          "tweet_volume": ""
        },
        {
          "name": "Sabres",
          "tweet_volume": ""
        },
        {
          "name": "AJ Styles",
          "tweet_volume": ""
        },
        {
          "name": "Arthur Blank",
          "tweet_volume": ""
        },
        {
          "name": "Puca",
          "tweet_volume": ""
        },
        {
          "name": "Blake Corum",
          "tweet_volume": ""
        },
        {
          "name": "Redban",
          "tweet_volume": ""
        },
        {
          "name": "THATS A CATCH",
          "tweet_volume": ""
        },
        {
          "name": "Xavier Smith",
          "tweet_volume": ""
        },
        {
          "name": "Jessie Bates",
          "tweet_volume": ""
        },
        {
          "name": "NFL MVP",
          "tweet_volume": ""
        },
        {
          "name": "Ernest Borgnine",
          "tweet_volume": ""
        },
        {
          "name": "Raquel",
          "tweet_volume": "17K"
        },
        {
          "name": "Saints",
          "tweet_volume": "21K"
        },
        {
          "name": "Penta",
          "tweet_volume": ""
        },
        {
          "name": "Diawara",
          "tweet_volume": ""
        },
        {
          "name": "Saddiq Bey",
          "tweet_volume": ""
        },
        {
          "name": "Kyren Williams",
          "tweet_volume": ""
        },
        {
          "name": "Manus",
          "tweet_volume": "13K"
        }
      ],
      "timestamp": 1767071410
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Rams",
          "tweet_volume": "37K"
        },
        {
          "name": "Falcons",
          "tweet_volume": "23K"
        },
        {
          "name": "#WWERaw",
          "tweet_volume": "32K"
        },
        {
          "name": "Stafford",
          "tweet_volume": "21K"
        },
        {
          "name": "Bijan",
          "tweet_volume": "17K"
        },
        {
          "name": "Xavier Watts",
          "tweet_volume": ""
        },
        {
          "name": "Drake Maye",
          "tweet_volume": "17K"
        },
        {
          "name": "Austin Theory",
          "tweet_volume": ""
        },
        {
          "name": "#LARvsATL",
          "tweet_volume": ""
        },
        {
          "name": "DJ Humphries",
          "tweet_volume": ""
        },
        {
          "name": "The 5th",
          "tweet_volume": "52K"
        },
        {
          "name": "Nikki",
          "tweet_volume": "29K"
        },
        {
          "name": "#RawonNetflix",
          "tweet_volume": ""
        },
        {
          "name": "Raheem",
          "tweet_volume": ""
        },
        {
          "name": "#DirtyBirds",
          "tweet_volume": ""
        },
        {
          "name": "McVay",
          "tweet_volume": ""
        },
        {
          "name": "Puka",
          "tweet_volume": "11K"
        },
        {
          "name": "Jessie Bates",
          "tweet_volume": ""
        },
        {
          "name": "#RiseUp",
          "tweet_volume": ""
        },
        {
          "name": "Raquel",
          "tweet_volume": "16K"
        },
        {
          "name": "Kirk Cousins",
          "tweet_volume": ""
        },
        {
          "name": "Saddiq Bey",
          "tweet_volume": ""
        },
        {
          "name": "Penta",
          "tweet_volume": ""
        },
        {
          "name": "Redban",
          "tweet_volume": ""
        },
        {
          "name": "Denny",
          "tweet_volume": ""
        },
        {
          "name": "Stephanie",
          "tweet_volume": "12K"
        },
        {
          "name": "R-Truth",
          "tweet_volume": ""
        },
        {
          "name": "Brandon Miller",
          "tweet_volume": ""
        },
        {
          "name": "The Vision",
          "tweet_volume": "64K"
        },
        {
          "name": "Diawara",
          "tweet_volume": ""
        },
        {
          "name": "Tre Johnson",
          "tweet_volume": ""
        },
        {
          "name": "Maxxine",
          "tweet_volume": ""
        },
        {
          "name": "Jared Verse",
          "tweet_volume": ""
        },
        {
          "name": "Spencer Jones",
          "tweet_volume": ""
        },
        {
          "name": "Bron Breakker",
          "tweet_volume": ""
        },
        {
          "name": "Nikola Jokic",
          "tweet_volume": ""
        },
        {
          "name": "Iran",
          "tweet_volume": "354K"
        },
        {
          "name": "Cornell",
          "tweet_volume": ""
        },
        {
          "name": "Will Richard",
          "tweet_volume": ""
        },
        {
          "name": "Dragon Lee",
          "tweet_volume": ""
        },
        {
          "name": "Blake Corum",
          "tweet_volume": ""
        },
        {
          "name": "Manus",
          "tweet_volume": "11K"
        },
        {
          "name": "Usos",
          "tweet_volume": ""
        },
        {
          "name": "CM Punk",
          "tweet_volume": ""
        },
        {
          "name": "Ernest Borgnine",
          "tweet_volume": ""
        },
        {
          "name": "Becky Lynch",
          "tweet_volume": ""
        },
        {
          "name": "Yabu",
          "tweet_volume": ""
        },
        {
          "name": "Jack Benter",
          "tweet_volume": ""
        },
        {
          "name": "Bobby Portis",
          "tweet_volume": ""
        },
        {
          "name": "Kyren Williams",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767065620
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Denny",
          "tweet_volume": ""
        },
        {
          "name": "Iran",
          "tweet_volume": "317K"
        },
        {
          "name": "Netanyahu",
          "tweet_volume": "241K"
        },
        {
          "name": "Puka",
          "tweet_volume": ""
        },
        {
          "name": "Bijan",
          "tweet_volume": ""
        },
        {
          "name": "Manus",
          "tweet_volume": ""
        },
        {
          "name": "Falcons",
          "tweet_volume": "11K"
        },
        {
          "name": "Trey Lance",
          "tweet_volume": ""
        },
        {
          "name": "The 5th",
          "tweet_volume": "51K"
        },
        {
          "name": "Israel Prize",
          "tweet_volume": ""
        },
        {
          "name": "Garrett Riley",
          "tweet_volume": ""
        },
        {
          "name": "Jessica Tarlov",
          "tweet_volume": ""
        },
        {
          "name": "Jacksepticeye",
          "tweet_volume": ""
        },
        {
          "name": "Kyren",
          "tweet_volume": ""
        },
        {
          "name": "Bibi",
          "tweet_volume": "32K"
        },
        {
          "name": "Whale - $SOL",
          "tweet_volume": ""
        },
        {
          "name": "Mickey Conn",
          "tweet_volume": ""
        },
        {
          "name": "Monday Night Football",
          "tweet_volume": ""
        },
        {
          "name": "Auburn",
          "tweet_volume": ""
        },
        {
          "name": "Drake London",
          "tweet_volume": ""
        },
        {
          "name": "Anthony Joshua",
          "tweet_volume": "228K"
        },
        {
          "name": "Jerome Powell",
          "tweet_volume": "11K"
        },
        {
          "name": "AI - $SOL",
          "tweet_volume": ""
        },
        {
          "name": "Lincoln Riley",
          "tweet_volume": ""
        },
        {
          "name": "Dale Evans",
          "tweet_volume": ""
        },
        {
          "name": "Alfred Hitchcock",
          "tweet_volume": ""
        },
        {
          "name": "Roy Rogers",
          "tweet_volume": ""
        },
        {
          "name": "Bussi",
          "tweet_volume": ""
        },
        {
          "name": "Slovakia",
          "tweet_volume": ""
        },
        {
          "name": "Mustard",
          "tweet_volume": ""
        },
        {
          "name": "Freemasons",
          "tweet_volume": ""
        },
        {
          "name": "Trae",
          "tweet_volume": "18K"
        },
        {
          "name": "Cam Coleman",
          "tweet_volume": ""
        },
        {
          "name": "Diosdado Cabello",
          "tweet_volume": ""
        },
        {
          "name": "Resign",
          "tweet_volume": "61K"
        },
        {
          "name": "Jazzy Davidson",
          "tweet_volume": ""
        },
        {
          "name": "Chappell",
          "tweet_volume": "14K"
        },
        {
          "name": "Wilma",
          "tweet_volume": ""
        },
        {
          "name": "App State",
          "tweet_volume": ""
        },
        {
          "name": "#minnesotacorruption",
          "tweet_volume": ""
        },
        {
          "name": "Shah",
          "tweet_volume": "87K"
        },
        {
          "name": "Blake Corum",
          "tweet_volume": ""
        },
        {
          "name": "Georgia Southern",
          "tweet_volume": ""
        },
        {
          "name": "Mayhem",
          "tweet_volume": ""
        },
        {
          "name": "Dabo",
          "tweet_volume": ""
        },
        {
          "name": "#DirtyBirds",
          "tweet_volume": ""
        },
        {
          "name": "Greene",
          "tweet_volume": "23K"
        },
        {
          "name": "The Birds",
          "tweet_volume": "16K"
        },
        {
          "name": "Cornell",
          "tweet_volume": ""
        },
        {
          "name": "Magazines",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767055962
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Minnesota",
          "tweet_volume": "1.4M"
        },
        {
          "name": "49ers",
          "tweet_volume": "88K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "117K"
        },
        {
          "name": "Josh Allen",
          "tweet_volume": "50K"
        },
        {
          "name": "Steelers",
          "tweet_volume": "120K"
        },
        {
          "name": "Bills",
          "tweet_volume": "135K"
        },
        {
          "name": "FINALLY DID IT",
          "tweet_volume": "37K"
        },
        {
          "name": "Bears",
          "tweet_volume": "127K"
        },
        {
          "name": "Niners",
          "tweet_volume": "22K"
        },
        {
          "name": "Somali",
          "tweet_volume": "924K"
        },
        {
          "name": "Browns",
          "tweet_volume": "91K"
        },
        {
          "name": "HOBI",
          "tweet_volume": "25K"
        },
        {
          "name": "Brock Purdy",
          "tweet_volume": "31K"
        },
        {
          "name": "Good Monday",
          "tweet_volume": "36K"
        },
        {
          "name": "Nick Shirley",
          "tweet_volume": "544K"
        },
        {
          "name": "Tomlin",
          "tweet_volume": "29K"
        },
        {
          "name": "Ravens",
          "tweet_volume": "67K"
        },
        {
          "name": "Jets",
          "tweet_volume": "65K"
        },
        {
          "name": "Caleb",
          "tweet_volume": "80K"
        },
        {
          "name": "Panthers",
          "tweet_volume": "39K"
        },
        {
          "name": "#FTTB",
          "tweet_volume": "12K"
        },
        {
          "name": "Tim Walz",
          "tweet_volume": "550K"
        },
        {
          "name": "Raiders",
          "tweet_volume": "42K"
        },
        {
          "name": "Monday of 2025",
          "tweet_volume": "11K"
        },
        {
          "name": "Giants",
          "tweet_volume": "50K"
        },
        {
          "name": "Bucs",
          "tweet_volume": "19K"
        },
        {
          "name": "Kawhi",
          "tweet_volume": "22K"
        },
        {
          "name": "Luther Burden",
          "tweet_volume": ""
        },
        {
          "name": "Brigitte Bardot",
          "tweet_volume": "359K"
        },
        {
          "name": "#MondayMotivation",
          "tweet_volume": ""
        },
        {
          "name": "Putin",
          "tweet_volume": "336K"
        },
        {
          "name": "Buffalo",
          "tweet_volume": "29K"
        },
        {
          "name": "#BLACKWHALE",
          "tweet_volume": ""
        },
        {
          "name": "Chargers",
          "tweet_volume": "18K"
        },
        {
          "name": "#CHIvsSF",
          "tweet_volume": ""
        },
        {
          "name": "The Jupiter",
          "tweet_volume": "37K"
        },
        {
          "name": "Rodgers",
          "tweet_volume": "23K"
        },
        {
          "name": "joe brady",
          "tweet_volume": ""
        },
        {
          "name": "Zelensky",
          "tweet_volume": "221K"
        },
        {
          "name": "Danielle",
          "tweet_volume": "158K"
        },
        {
          "name": "#AEWWorldsEnd",
          "tweet_volume": "12K"
        },
        {
          "name": "Derrick Henry",
          "tweet_volume": "17K"
        },
        {
          "name": "Seahawks",
          "tweet_volume": "43K"
        },
        {
          "name": "Garrett",
          "tweet_volume": "24K"
        },
        {
          "name": "Texans",
          "tweet_volume": "22K"
        },
        {
          "name": "Learing",
          "tweet_volume": "97K"
        },
        {
          "name": "Ukraine",
          "tweet_volume": "535K"
        },
        {
          "name": "Jalen Carter",
          "tweet_volume": ""
        },
        {
          "name": "Cam Ward",
          "tweet_volume": ""
        },
        {
          "name": "Malik Willis",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1767017319
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Chinese W",
          "tweet_volume": ""
        },
        {
          "name": "Good Monday",
          "tweet_volume": "31K"
        },
        {
          "name": "#NIKKE2026NewYear",
          "tweet_volume": ""
        },
        {
          "name": "49ers",
          "tweet_volume": "86K"
        },
        {
          "name": "Bears",
          "tweet_volume": "126K"
        },
        {
          "name": "Niners",
          "tweet_volume": "22K"
        },
        {
          "name": "#MondayMotivation",
          "tweet_volume": ""
        },
        {
          "name": "Monday of 2025",
          "tweet_volume": ""
        },
        {
          "name": "#STARDOM",
          "tweet_volume": ""
        },
        {
          "name": "Caleb",
          "tweet_volume": "81K"
        },
        {
          "name": "Danielle",
          "tweet_volume": "139K"
        },
        {
          "name": "Purdy",
          "tweet_volume": "49K"
        },
        {
          "name": "Kawhi",
          "tweet_volume": "21K"
        },
        {
          "name": "#FTTB",
          "tweet_volume": "11K"
        },
        {
          "name": "Taiwan",
          "tweet_volume": "59K"
        },
        {
          "name": "ADOR",
          "tweet_volume": "96K"
        },
        {
          "name": "#BaddiesUSA",
          "tweet_volume": "19K"
        },
        {
          "name": "Swift",
          "tweet_volume": "55K"
        },
        {
          "name": "Luther",
          "tweet_volume": "16K"
        },
        {
          "name": "NewJeans",
          "tweet_volume": "196K"
        },
        {
          "name": "Warner",
          "tweet_volume": "12K"
        },
        {
          "name": "Tommie",
          "tweet_volume": ""
        },
        {
          "name": "Bosa",
          "tweet_volume": "13K"
        },
        {
          "name": "Wizkid",
          "tweet_volume": "171K"
        },
        {
          "name": "Kyle Shanahan",
          "tweet_volume": ""
        },
        {
          "name": "DJ Moore",
          "tweet_volume": ""
        },
        {
          "name": "Collinsworth",
          "tweet_volume": ""
        },
        {
          "name": "Ben Johnson",
          "tweet_volume": "11K"
        },
        {
          "name": "Dennis Allen",
          "tweet_volume": ""
        },
        {
          "name": "Kittle",
          "tweet_volume": ""
        },
        {
          "name": "Nick Smith",
          "tweet_volume": ""
        },
        {
          "name": "Jennings",
          "tweet_volume": "15K"
        },
        {
          "name": "Tavi",
          "tweet_volume": ""
        },
        {
          "name": "Aiyuk",
          "tweet_volume": ""
        },
        {
          "name": "Marsh",
          "tweet_volume": ""
        },
        {
          "name": "Harmeet",
          "tweet_volume": ""
        },
        {
          "name": "NFC West",
          "tweet_volume": ""
        },
        {
          "name": "Trent",
          "tweet_volume": ""
        },
        {
          "name": "Saleh",
          "tweet_volume": ""
        },
        {
          "name": "Santa Clara",
          "tweet_volume": ""
        },
        {
          "name": "Chrisean",
          "tweet_volume": ""
        },
        {
          "name": "Mac Jones",
          "tweet_volume": ""
        },
        {
          "name": "Bijan",
          "tweet_volume": ""
        },
        {
          "name": "Sunday Night Football",
          "tweet_volume": ""
        },
        {
          "name": "Hasan",
          "tweet_volume": "23K"
        },
        {
          "name": "Barzal",
          "tweet_volume": ""
        },
        {
          "name": "NFC Championship",
          "tweet_volume": ""
        },
        {
          "name": "Zeus",
          "tweet_volume": "12K"
        },
        {
          "name": "Chinese W",
          "tweet_volume": ""
        },
        {
          "name": "Good Monday",
          "tweet_volume": "31K"
        }
      ],
      "timestamp": 1767009161
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "49ers",
          "tweet_volume": "80K"
        },
        {
          "name": "49ers",
          "tweet_volume": "80K"
        },
        {
          "name": "Niners",
          "tweet_volume": "20K"
        },
        {
          "name": "Caleb",
          "tweet_volume": "83K"
        },
        {
          "name": "Brock Purdy",
          "tweet_volume": "27K"
        },
        {
          "name": "#FTTB",
          "tweet_volume": "11K"
        },
        {
          "name": "Kawhi",
          "tweet_volume": "16K"
        },
        {
          "name": "Danielle",
          "tweet_volume": "93K"
        },
        {
          "name": "Swift",
          "tweet_volume": "54K"
        },
        {
          "name": "Luther Burden",
          "tweet_volume": ""
        },
        {
          "name": "Seahawks",
          "tweet_volume": "40K"
        },
        {
          "name": "Collinsworth",
          "tweet_volume": ""
        },
        {
          "name": "Ben Johnson",
          "tweet_volume": "10K"
        },
        {
          "name": "#BaddiesUSA",
          "tweet_volume": "15K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "119K"
        },
        {
          "name": "#CHIvsSF",
          "tweet_volume": ""
        },
        {
          "name": "Bosa",
          "tweet_volume": "13K"
        },
        {
          "name": "DJ Moore",
          "tweet_volume": ""
        },
        {
          "name": "#SNFonNBC",
          "tweet_volume": ""
        },
        {
          "name": "Kyle Shanahan",
          "tweet_volume": ""
        },
        {
          "name": "Warner",
          "tweet_volume": "12K"
        },
        {
          "name": "Josh Allen",
          "tweet_volume": "46K"
        },
        {
          "name": "Bills",
          "tweet_volume": "131K"
        },
        {
          "name": "WHAT A GAME",
          "tweet_volume": "47K"
        },
        {
          "name": "Jennings",
          "tweet_volume": "15K"
        },
        {
          "name": "Loveland",
          "tweet_volume": ""
        },
        {
          "name": "Chase Lucas",
          "tweet_volume": ""
        },
        {
          "name": "#BearDown",
          "tweet_volume": ""
        },
        {
          "name": "NFC West",
          "tweet_volume": ""
        },
        {
          "name": "Tommie",
          "tweet_volume": ""
        },
        {
          "name": "Saleh",
          "tweet_volume": ""
        },
        {
          "name": "Trent Williams",
          "tweet_volume": ""
        },
        {
          "name": "Defense",
          "tweet_volume": "200K"
        },
        {
          "name": "ADOR",
          "tweet_volume": "67K"
        },
        {
          "name": "Kittle",
          "tweet_volume": ""
        },
        {
          "name": "Nick Smith",
          "tweet_volume": ""
        },
        {
          "name": "NewJeans",
          "tweet_volume": "138K"
        },
        {
          "name": "Sunday Night Football",
          "tweet_volume": ""
        },
        {
          "name": "Game of the Year",
          "tweet_volume": "20K"
        },
        {
          "name": "Aiyuk",
          "tweet_volume": ""
        },
        {
          "name": "Santa Clara",
          "tweet_volume": ""
        },
        {
          "name": "Mac Jones",
          "tweet_volume": ""
        },
        {
          "name": "Marsh",
          "tweet_volume": ""
        },
        {
          "name": "Pistons",
          "tweet_volume": ""
        },
        {
          "name": "Stafford",
          "tweet_volume": ""
        },
        {
          "name": "Tavi",
          "tweet_volume": ""
        },
        {
          "name": "Harmeet",
          "tweet_volume": ""
        },
        {
          "name": "Philly",
          "tweet_volume": "14K"
        },
        {
          "name": "Seattle",
          "tweet_volume": "36K"
        },
        {
          "name": "Hurts",
          "tweet_volume": "74K"
        }
      ],
      "timestamp": 1766995661
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Josh Allen",
          "tweet_volume": "36K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "112K"
        },
        {
          "name": "49ers",
          "tweet_volume": "34K"
        },
        {
          "name": "Purdy",
          "tweet_volume": "13K"
        },
        {
          "name": "Caleb",
          "tweet_volume": "70K"
        },
        {
          "name": "Niners",
          "tweet_volume": ""
        },
        {
          "name": "#BaddiesUSA",
          "tweet_volume": ""
        },
        {
          "name": "#FTTB",
          "tweet_volume": ""
        },
        {
          "name": "#CHIvsSF",
          "tweet_volume": ""
        },
        {
          "name": "Luther",
          "tweet_volume": "11K"
        },
        {
          "name": "Joe Brady",
          "tweet_volume": ""
        },
        {
          "name": "Jalen",
          "tweet_volume": "29K"
        },
        {
          "name": "Buffalo",
          "tweet_volume": "29K"
        },
        {
          "name": "Pick 6",
          "tweet_volume": ""
        },
        {
          "name": "AFC East",
          "tweet_volume": "18K"
        },
        {
          "name": "#SNFonNBC",
          "tweet_volume": ""
        },
        {
          "name": "#90dayfiancebeforethe90days",
          "tweet_volume": ""
        },
        {
          "name": "Trent Williams",
          "tweet_volume": ""
        },
        {
          "name": "Patullo",
          "tweet_volume": ""
        },
        {
          "name": "McDermott",
          "tweet_volume": ""
        },
        {
          "name": "Tommie",
          "tweet_volume": ""
        },
        {
          "name": "Steelers",
          "tweet_volume": "111K"
        },
        {
          "name": "Jaylon Johnson",
          "tweet_volume": ""
        },
        {
          "name": "Austin Booker",
          "tweet_volume": ""
        },
        {
          "name": "Raiders",
          "tweet_volume": "40K"
        },
        {
          "name": "Giants",
          "tweet_volume": "46K"
        },
        {
          "name": "Jake Claver",
          "tweet_volume": ""
        },
        {
          "name": "Sirianni",
          "tweet_volume": ""
        },
        {
          "name": "Tavi",
          "tweet_volume": ""
        },
        {
          "name": "Marchment",
          "tweet_volume": ""
        },
        {
          "name": "Patriots",
          "tweet_volume": "133K"
        },
        {
          "name": "Browns",
          "tweet_volume": "89K"
        },
        {
          "name": "Montez Sweat",
          "tweet_volume": ""
        },
        {
          "name": "Collinsworth",
          "tweet_volume": ""
        },
        {
          "name": "Tomlin",
          "tweet_volume": "26K"
        },
        {
          "name": "Barzal",
          "tweet_volume": ""
        },
        {
          "name": "Pats",
          "tweet_volume": "19K"
        },
        {
          "name": "Shakir",
          "tweet_volume": ""
        },
        {
          "name": "Jake Tonges",
          "tweet_volume": ""
        },
        {
          "name": "Putin",
          "tweet_volume": "268K"
        },
        {
          "name": "Jets",
          "tweet_volume": "65K"
        },
        {
          "name": "Chrisean",
          "tweet_volume": ""
        },
        {
          "name": "Cooks",
          "tweet_volume": ""
        },
        {
          "name": "Colston Loveland",
          "tweet_volume": ""
        },
        {
          "name": "Mendoza",
          "tweet_volume": "31K"
        },
        {
          "name": "Harmeet",
          "tweet_volume": ""
        },
        {
          "name": "Ricky Pearsall",
          "tweet_volume": ""
        },
        {
          "name": "Ahna",
          "tweet_volume": ""
        },
        {
          "name": "DJ Sky",
          "tweet_volume": ""
        },
        {
          "name": "Badgley",
          "tweet_volume": ""
        }
      ],
      "timestamp": 1766977951
    }
  },
  {
    "data": {
      "trends": [
        {
          "name": "Josh Allen",
          "tweet_volume": "15K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "78K"
        },
        {
          "name": "Eagles",
          "tweet_volume": "78K"
        },
        {
          "name": "Jalen Carter",
          "tweet_volume": ""
        },
        {
          "name": "Giants",
          "tweet_volume": "39K"
        },
        {
          "name": "Raiders",
          "tweet_volume": "35K"
        },
        {
          "name": "Steelers",
          "tweet_volume": "100K"
        },
        {
          "name": "Joe Brady",
          "tweet_volume": ""
        },
        {
          "name": "Browns",
          "tweet_volume": "81K"
        },
        {
          "name": "Tomlin",
          "tweet_volume": "23K"
        },
        {
          "name": "Patullo",
          "tweet_volume": ""
        },
        {
          "name": "Tom Brady",
          "tweet_volume": ""
        },
        {
          "name": "Smitty",
          "tweet_volume": ""
        },
        {
          "name": "#PHIvsBUF",
          "tweet_volume": ""
        },
        {
          "name": "Scottie Barnes",
          "tweet_volume": ""
        },
        {
          "name": "Geno",
          "tweet_volume": ""
        },
        {
          "name": "Jets",
          "tweet_volume": "59K"
        },
        {
          "name": "Deonte Banks",
          "tweet_volume": ""
        },
        {
          "name": "Panthers",
          "tweet_volume": "32K"
        },
        {
          "name": "Bucs",
          "tweet_volume": "15K"
        },
        {
          "name": "Rodgers",
          "tweet_volume": "21K"
        },
        {
          "name": "Putin",
          "tweet_volume": "240K"
        },
        {
          "name": "Marchment",
          "tweet_volume": ""
        },
        {
          "name": "#RaiderNation",
          "tweet_volume": ""
        },
        {
          "name": "Sirianni",
          "tweet_volume": ""
        },
        {
          "name": "Dart",
          "tweet_volume": "11K"
        },
        {
          "name": "Barzal",
          "tweet_volume": ""
        },
        {
          "name": "Shavers",
          "tweet_volume": ""
        },
        {
          "name": "Ravens",
          "tweet_volume": "94K"
        },
        {
          "name": "Cam Ward",
          "tweet_volume": ""
        },
        {
          "name": "Shough",
          "tweet_volume": "17K"
        },
        {
          "name": "Epps",
          "tweet_volume": ""
        },
        {
          "name": "McDermott",
          "tweet_volume": ""
        },
        {
          "name": "Shedeur",
          "tweet_volume": "29K"
        },
        {
          "name": "Vic Fangio",
          "tweet_volume": ""
        },
        {
          "name": "#BlackWhale",
          "tweet_volume": ""
        },
        {
          "name": "Jalyx Hunt",
          "tweet_volume": ""
        },
        {
          "name": "Garrett",
          "tweet_volume": "20K"
        },
        {
          "name": "AJ Brown",
          "tweet_volume": ""
        },
        {
          "name": "Drake Maye",
          "tweet_volume": "27K"
        },
        {
          "name": "Shipley",
          "tweet_volume": ""
        },
        {
          "name": "Saints",
          "tweet_volume": "32K"
        },
        {
          "name": "Pittsburgh",
          "tweet_volume": "16K"
        },
        {
          "name": "Cam Jurgens",
          "tweet_volume": ""
        },
        {
          "name": "Saquon",
          "tweet_volume": ""
        },
        {
          "name": "Raptors",
          "tweet_volume": ""
        },
        {
          "name": "Zelensky",
          "tweet_volume": "151K"
        },
        {
          "name": "Devonta",
          "tweet_volume": ""
        },
        {
          "name": "Schaefer",
          "tweet_volume": ""
        },
        {
          "name": "Baker",
          "tweet_volume": "18K"
        }
      ],
      "timestamp": 1766969307
    }
  }
]
  </code>
</pre>
