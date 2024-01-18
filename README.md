# Monitoring-suhu-udara
Monitoring suhu udara lewat web dengan ESP8266 dan sensor DHT 11
ESP8266 bertindak sebagai AP(Access point) yang mana nanti akan memunculkan wifi dengan nama "Dht web server". ketika kalian menyambungkan perangkat kalian ke SSID "Dht web server" nantinya akan otomatis masuk ke browser dan akan ditampilkan temperatur dan kelembaban hasil pembacaan sensor DHT 11

untuk wiring kalian harus menghubungkan pin D7(GPIO 13) pada node mcu (disini sasya menggunakan node mcu kalau kalian menggunakan model board esp8266 yang lain tinggal sesuaikan saja wiringnya ke pin GPIO 13)

