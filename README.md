# \<gl-style\>

gl-style for web components

## วิธีการใช้งานติดตั้ง

```
$ bower install 9lon-gl-styles --save
```

## วิธีการใช้งาน gl-color
import ไฟล์ gl-color ในหน้าที่่ต้องการใช้
```
 <link rel="import" href="bower_components/gl-styles/gl-color.html">
```
ให้คุณแทรก gl-color ใน แทรก style ในหน้าที่คุณต้องใช้งาน
```
<style is="custom-style" include="gl-color"></style>
```
ต่อมาก็แทรก css ดังตัวอย่างด้านล่างลงไปใน สไตล์ที่คุณต้องการจะเปลี่ยน 
```
    div.ex {
        color:var(--gl-primary-color);
    }
```

## Color variables
![alt text](http://i.imgur.com/DTyUDJv.png "gl-color")
```
        --gl-primary-color
        --gl-success-color
        --gl-info-color
        --gl-warning-color
        --gl-danger-color

        --gl-gray-darker-color
        --gl-gray-dark-color
        --gl-gray-color
        --gl-gray-light-color
        --gl-gray-lighter-color

        --gl-white-color

        --gl-primary-font-color
        --gl-success-font-color
        --gl-info-font-color
        --gl-warning-font-color
        --gl-danger-font-color
```
## BG-Color variables
![alt text](http://i.imgur.com/s3gHS4Q.png "gl-bg-color")
```
        .gl-bg-primary
        .gl-bg-success
        .gl-bg-info
        .gl-bg-warning
        .gl-bg-danger
```
วิธีการใช้งาน
```
    <p class="gl-bg-primary">gl-bg-primary</p>
```

## วิธีการใช้งาน gl-size
import ไฟล์ gl-size ในหน้าที่่ต้องการใช้
```
 <link rel="import" href="bower_components/gl-styles/gl-size.html">
```
ให้คุณแทรก gl-size ใน แทรก style ในหน้าที่คุณต้องใช้งาน
```
<style is="custom-style" include="gl-size"></style>
```
ต่อมาก็แทรก css ดังตัวอย่างด้านล่างลงไปใน สไตล์ที่คุณต้องการจะเปลี่ยน 
```
    <button class="ex-small">ex-small</button>
```
## Size class 
![alt text](http://i.imgur.com/00Ah52X.png "gl-color")
```
        .gl-ex-large
        .gl-large
        .gl-default
        .gl-small
        .gl-ex-small

```
## วิธีการใช้งาน  font size variables 
```
        font-size: var(--font-size-large);
```
##  Font size variables 
```
       --font-size-default:        14px;
       --font-size-large:         ~18px
       --font-size-small:         ~12px
       --font-size-h1:            ~36px
       --font-size-h2:            ~30px
       --font-size-h3:            ~24px
       --font-size-h4:            ~18px
       --font-size-h5:             14px;
       --font-size-h6:            ~12px
```


