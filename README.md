# Qr-code-for-laser-cut
An important description of the experience for using qr code for laser cutting.  

## Main idea

**I consider it important to add qr code to ready-made models, organically fitting them into the design, as far as possible, because this will help other users repeat your project, modify it, understand how and why to use it, as well as in case of a breakdown, understand how to fix it, spending the least amount of time on what you have already invented**    

## My experinece

In  [Organizer-for-a-drill-parts-poject](https://github.com/m2415146/Organizer-for-a-drill-parts) , I had the need to use qr code for laser cutting. at the moment, I am using a combination of creating a surface in the rhinoceros program, further exporting to .dxf format and further adapting for cutting in the CorelDRAW program  

## Making a QR code online  

it turned out that inserting QR into RHino, as well as into CorelDRAW itself, is not such an easy task. QR can be created using various services - for example, such:
[QR code generator](http://qrcoder.ru/?t=1/)  

![Screenshot_161](https://github.com/user-attachments/assets/a5599b44-f21e-4453-97b3-9b0385bd0bb2)  

but when you try to import it into rhino, it is inserted as a simple picture, which is not suitable for uploading to CorelDraw for laser cutting. Also, if you insert it into CorelDraw itself, you will encounter problems.  

It may looks like this:  

![Screenshot_162](https://github.com/user-attachments/assets/4a574b18-ec77-4304-b82f-dde4c58323a7)  

I also tried using a QR code generator for 3D printing ( [QR code 2 stl](https://printer.tools/qrcode2stl/#shareQR-eyJ0ZXh0IjoiaHR0cHM6Ly9naXRodWIuY29tL20yNDE1MTQ2L09yZ2FuaXplci1mb3ItYS1kcmlsbC1wYXJ0cyJ9) )   - you get a stl model that looks like this in CorelDraw:  

![Screenshot_163](https://github.com/user-attachments/assets/84d09db4-c195-4440-b6fe-c042b681db0a)  

This how il looks like in rhino. I think it can be a convenient tool for 3D printing and then coloring the code manually or printing with 2 colors.  

![Screenshot_165](https://github.com/user-attachments/assets/42e97251-1ec0-4cc3-aa72-b3f2b7c1e433)


## Qr code plugin in Rhinoceros  

I also found a plugin for RHino that generates a QR code, but I couldn’t figure out how to use it  [QR Rhino](https://www.food4rhino.com/en/resource/qr-code-generator)   

## Making Qr code in COrelDraw

I want to test the qr code generator in the CorelDRAW program for this task.  

Unfortunately, CorelDRAW generates a Qr code that turns out to be too small to cut on a laser machine 

![photo_5346208113210025771_y](https://github.com/user-attachments/assets/dcf3cd1d-d844-4869-a6b1-80a0b97f13a7)  

during the simulation in the program, it is read from the computer screen by the phone, whereas during laser cutting the image remains readable, but is not perceived by the phone as a link  

Several attempts have been made using two-tone acrylic and an acrylic-like material. the result turned out to be the same during all attempts  

![photo_5343948964707296411_y](https://github.com/user-attachments/assets/ccfc2bd6-b934-428e-9afd-e72ed9b16ded)  

![photo_5330043097553429044_y](https://github.com/user-attachments/assets/bf126a16-8a62-4ac3-83da-b09ff259de7e)  

**CorelDRAW allows you to generate a QR code, but does not allow you to edit its design, which makes it difficult to use it in cases where it is difficult to achieve high image accuracy**  

## Results  

**in my experience, if you need to create a qr code for laser cutting, about 4*5 cm in size, you need to abandon such an idea after considering other options**  

## Another opportunities  

1) **change the scale if possible**  

we make the QR code larger and it becomes easier to engrave small details  

2) **try to find a way that will allow you to create a QR code from larger elements**

if I couldn't find one, it doesn't mean that it doesn't exist. please, if you find a similar way, let me know

3) **change qr code to text link**

It won’t look as harmonious, but it will work and it will be easier to make it readable on a phone. since there is a dependence between the number of characters in the link and the detail of the qr code, it is possible to use services that allow you to make the link shorter - perhaps this will solve this problem

![photo_5343948964707296415_y](https://github.com/user-attachments/assets/17e40b23-2e1d-465d-b04d-8e770e8afd13)






