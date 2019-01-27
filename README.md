# cssresponsiveAlya
1. Kenapa kita perlu membuat web dengan responsive?

    -Supaya web yang kita buat menyesuaikan diri agar sesuai dengan layar apa pun, sehingga membuat tampilan website tetap mulus di          antara berbagai media. Artinya, situsnya akan berubah sesuai layar yang dilihatnya. 
2. Bagaimana cara membuat web dengan responsive? Jelaskan!

    <html lang="en" dir="ltr">  
    <head>
        <meta charset="utf-8>"> 
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <Title>Background</Title>
        <style media="screen">
        body{
            background: blue;
            color: white;
        }
        @media only screen and (min-width: 600px){       
            body{            
                background: lightcoral;                
                color:crimson;          
            }           
        }       
        @media only screen and (min-width: 768px){        
            body{          
                background: darkgoldenrod;             
                color: azure;              
            }            
        }        
        </style>        
    </head>    
    <body>    
        <h1>Welcome to SMK Telkom Malang</h1>       
    </body>    
  </html>
  
  
    Penjelasan:
    -<meta name="viewport" content="width=device-width, initial-scale=1.0">
    merupakan syntax yang berfungsi untuk menampilkan web sesuai dengan layar.
    - @media only screen and (min-width: 600px){
            body{
            }
        }
        sedangkan yang diatas ini untuk menampilkan layar.
    
3. Apa maksud dari kode "initial- scale=1.0” ?

      initial-scale=1.0 bagian menetapkan tingkat zoom awal saat halaman pertama dimuat oleh browser
      
4. Bagian mana saja yang perlu kita atur/buat responsive dalam sebuah web!

      -mengatur viewport pada halaman web tersebut. Pengaturan tersebut dituliskan pada tag <meta> yang terdapat di dalam tag <head>.
    
      -menentukan struktur HTML website, website biasanya terdiri dari header, content, sidebar serta footer.
      
      -Membuat Media Query di CSS Untuk Memerintahkan Browser.
      
      
      
      HASIL LATIHAN
      LATIHAN 1
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/1.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/2.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/3.jpg)
      
      LATIHAN 2
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/4.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/5.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/6.jpg)
      
      LATIHAN 3
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/7.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/8.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/9.jpg)
      
      LATIHAN 4
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/10.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/11.jpg)
      
      ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/12.jpg)
      
     LATIHAN 5
     ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/13.jpg)
     
     ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/14.jpg)
     
     ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/15.jpg)
     
     LATIHAN 6
     ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/16.jpg)
     
     ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/17.jpg)
     
     ![alt text](https://github.com/AlyaSelviaTamzila/cssresponsiveAlya/blob/master/18.jpg)
