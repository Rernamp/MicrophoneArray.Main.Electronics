 [описание](CH32FV2x_V3xRM.PDF#page=335) какие пины пере используются вместе с SPI
 * SD(Serial Data) пин(Alias MOSI) - пин для приёма/передачи данных(2 канала вмещает в себя)
 * WS (Word Selection) пин(Alias Nss) - пин для выбора Master/Slave режима
 * CK (Serial clock) пин(Alias SCK) - пин с тактирование.
	 * Output для режима Master
	 * Input для режима Slave
* MCK пин
	* 256 x Fs