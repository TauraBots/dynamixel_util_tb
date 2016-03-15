# dynamixel_util_tb
Files to work with the dynimixel motors


Usage
-----
	C++
git clone https://github.com/TauraBots/dynamixel_util_tb.git

cd cpp

make dynamixel_test

Antes de executar deve-se dar permissão para a porta USB com o comando:

sudo chmod 777 /dev/ttyUSB0

Caso algum erro ocorra verifique se a placa está corretamente conectada, o comando

dmesg

poderá ajudar

./dynamixel_test [id]



