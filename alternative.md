
# Тестирование приложением:
![graphicbig](https://github.com/albel-t/SpeedTest/blob/main/graphicbig.png)
# Тестирование командой:
![testcommand](https://github.com/albel-t/SpeedTest/blob/main/testcommand.png)



# !Внимание!
#### Использование команд повлечет за собой повреждение флешки
* Команды:
```bash
sudo dd of=/dev/null if=/dev/sdc1 bs=1M count=100 iflag=direct status=progress
sudo dd if=/dev/random of=/dev/sdc1 bs=1M count=100 oflag=direct
```


