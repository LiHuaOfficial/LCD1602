# LCD1602
适用于51单片机驱动LCD1602的代码  
包含以下操作：  
```
/*x 1~2 y 0~16*/
LCD_init(void);//初始化LCD  
LCD_disp_char(uchar x,uchar y,uchar dat)//显示字符  
LCD_disp_string(uchar x,uchar y,uchar * str);//显示字符串（自动换行  
LCD_clear(void);//清屏  
LCD_disp_number(uchar x,uchar y,int dat);//显示数字，在int16范围内  
```
