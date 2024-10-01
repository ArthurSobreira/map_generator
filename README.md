# Generate Map From Image

* First of all, make sure you clone the repository with the following command:

```bash
$> git clone git@github.com:ArthurSobreira/map_generator.git
```

* Then, you need to install the <strong>Pillow</strong> and <strong>Numpy</strong> packages, with the following commands:

```bash
$> pip install numpy Pillow
```

* Now, to create properly formatted maps that can be read by <strong>FdF</strong>, simply have access to an image (PNG or JPG)
  and run the script <code>map_generator.py</code> with the following command:

```bash
$> python3 map_generator.py

Enter the image path: <image-name>
```

* Once the map has been generated, to render it you just need to run your fdf binary with it, this way you can generate some really cool maps, like these:

<br>

<div align="center">
   <table>
     <tr>
       <td style="border: 5px solid darkgray;">
        <a href="images/van-gogh.png" target="_blank">
            <img height=550 src="images/van-gogh.png">
         </a>
       </td>
     </tr>
   </table>
</div><br>
<div align="center">
   <table>
     <tr>
       <td style="border: 5px solid darkgray;">
         <a href="images/got_map.png" target="_blank">
            <img height=550 src="images/got_map.png">
         </a>
       </td>
     </tr>
   </table>
</div><br>
<div align="center">
   <table>
     <tr>
       <td style="border: 5px solid darkgray;">
         <a href="images/monalisa.png" target="_blank">
            <img height=550 src="images/monalisa.png">
         </a>
       </td>
     </tr>
   </table>
</div><br>
