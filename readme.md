scp
$cd /home/sun/sun/multi_radar_conv_lstm_500x500
$scp -r multi_radar_conv_lstm_500x500  sunfengzhen@148.70.23.92:/home/sunfengzhen/sun

run
sun@ubuntu:~/sun/radar_conv_lstm_501x501$ nohup python main_radar.py >out.log &
