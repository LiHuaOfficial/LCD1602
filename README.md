# LCD1602
适用于51单片机驱动LCD1602的代码  
包含以下操作：  
```
/*x 1~2 y 0~16*/
LCD_init(void);//初始化函数  
LCD_disp_char(uchar x,uchar y,uchar dat);  
LCD_disp_string(uchar x,uchar y,uchar * str);  
LCD_clear(void);  
LCD_disp_number(uchar x,uchar y,uint dat);//数字为正  
```
