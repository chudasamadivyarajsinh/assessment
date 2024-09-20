**Framework Web
Designing Assessment
Test 3**
* Create bootstrap image gallery (Lightbox gallery).
*  After execution of the code following result must be displayed.

* Make sure each business logic is denoted with appropriate comments and
make your code interactive and represent clean and clear output on your
console screen.
* Implement this code using following concepts
1. custom css
2. custom jQuery



### ans:-

```html
**Framework Web
Designing Assessment
Test 3**
* Create bootstrap image gallery (Lightbox gallery).
*  After execution of the code following result must be displayed.

* Make sure each business logic is denoted with appropriate comments and
make your code interactive and represent clean and clear output on your
console screen.
* Implement this code using following concepts
1. custom css
2. custom jQuery



### ans:-

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
<style>
    
    .img-fluid{
        width: 380px;
        height: 300px;
    }
</style>
</head>
<body>
    <!-- modal-1 -->
    <div class="modal" id="mymodal1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://wallpaper.forfun.com/fetch/54/54384b5fd4634be174c409ecf47a38be.jpeg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
     <!-- modal-2 -->
    <div class="modal" id="mymodal2">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/tom-and-jerry-photo-editing-edited.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>


        <!-- modal-3 -->
    <div class="modal" id="mymodal3">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/Tom-and-Jerry-are-seen-studying-at-night.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
<!-- modal-4 -->
    <div class="modal" id="mymodal4">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/tom-and-jerry-photo-png.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
<!-- modal-5 -->
    <div class="modal" id="mymodal5">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/tom-and-jerry-photo-editing-background-edited.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
    <!-- modal-6 -->
    <div class="modal" id="mymodal6">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS4qlPe17JxXFEomepbazYKeULzBQN_eK4DYkIdDasM5nFQZAHih8vpyP8hVtcPEk_0fR0&usqp=CAU" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
<!-- modal-7 -->
    <div class="modal" id="mymodal7">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/c67ded86-54bc-4c5c-a309-64e531c92b35.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
<!-- modal-8 -->
    <div class="modal" id="mymodal8">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/Chand-Sitara-Decoration-and-Tom-Jerry-are-seen-drinking-coffee.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
<!-- modal-9 -->
    <div class="modal" id="mymodal9">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button class="btn-close" type="button" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <img src="https://ashisheditz.com/wp-content/uploads/2024/02/Jari-and-Tom-have-taken-a-photo-wearing-a-gold-garland.jpg" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
    <div class="container d-flex flex-column gap-2 mx-5 my-0 ">
        
        <div class="row d-flex gap-2">

            <!-- image-1 -->
            <div class="col m-0 p-0 ">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal1">
                 <img src="https://wallpaper.forfun.com/fetch/54/54384b5fd4634be174c409ecf47a38be.jpeg" class="img-fluid" alt="">
                </button>
                </div>
                <!-- image-2 -->
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal2">
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/tom-and-jerry-photo-editing-edited.jpg" class="img-fluid" alt="">
            </button>
            </div>
            <!-- image-3 -->
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal3">
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/Tom-and-Jerry-are-seen-studying-at-night.jpg" class="img-fluid" alt="">
            </button>
            </div>
        </div>
        <!-- image-4 -->
        <div class="row d-flex gap-2">
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal4">
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/tom-and-jerry-photo-png.jpg" class="img-fluid" alt="">
            </button>
            </div>
            <!-- image-5 -->
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal5">
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/tom-and-jerry-photo-editing-background-edited.jpg" class="img-fluid" alt="">
            </button>
            </div>
            <!-- image-6 -->
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal6">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS4qlPe17JxXFEomepbazYKeULzBQN_eK4DYkIdDasM5nFQZAHih8vpyP8hVtcPEk_0fR0&usqp=CAU" class="img-fluid" alt="">
            </button>
            </div>
        </div>
        <!-- image-7 -->
        <div class="row d-flex gap-2">
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal7">
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/c67ded86-54bc-4c5c-a309-64e531c92b35.jpg" class="img-fluid" alt="">
            </button>
            </div>
            <!-- image-8 -->
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal8">
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/Chand-Sitara-Decoration-and-Tom-Jerry-are-seen-drinking-coffee.jpg" class="img-fluid" alt="">
            </button>
            </div>
            <!-- image-9 -->
            <div class="col m-0 p-0">
                <button type="button" class="btn" data-bs-toggle="modal" data-bs-target="#mymodal9"> 
                <img src="https://ashisheditz.com/wp-content/uploads/2024/02/Jari-and-Tom-have-taken-a-photo-wearing-a-gold-garland.jpg" class="img-fluid" alt="">
            </button>
            </div>
        </div>
    </div>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
</body>
</html>
```
```
