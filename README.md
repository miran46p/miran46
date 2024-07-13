            

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900&display=swap');
        *{
            font-family: "Poppins", sans-serif;
        }
        .profile{
            height: 440px;
            width: 440px;
        }
    </style>
</head>
<body>
    <!-- Navbar Start -->
    <header>
        <div class="w-full h-16 bg-white drop-shadow-lg flex items-center px-28 place-content-between fixed">
            <div class="logo text-4xl font-semibold cursor-pointer text-slate-900 hover:text-rose-500 tracking-wider">
                SAMRAT
            </div>
            <ul class="flex items-center font-semibold text-md">
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">HOME</li>
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">ABOUT</li>
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">SERVICES</li>
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">RESUME</li>
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">FAQ</li>
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">CLIENT</li>
                <li class="px-4 py-1.5 border-0 border-rose-600 hover:border-b-4 duration-150 ease-in cursor-pointer">CONTACT</li>
            </ul>
            <div class="flex space-x-4 text-xl">
                <a href="https://www.facebook.com/akib.anjum.5" target="_blank"><i class="fa-brands fa-facebook hover:text-sky-700 hover:scale-125 ease-in duration-150"></i></a>
                <a href="https://x.com/AnjumAkib" target="_blank"><i class="fa-brands fa-twitter hover:text-sky-600 hover:scale-125 ease-in duration-150"></i></a>
                <a href="https://www.instagram.com/itsakib16/" target="_blank"><i class="fa-brands fa-instagram hover:text-slate-600 hover:scale-125 ease-in duration-150"></i></a>
            </div>
        </div>
    </header>
    <!-- Navbar End -->


     <!-- Page-1 Start -->
    <div class="h-full bg-rose-500 pt-16 pb-16 px-28 flex place-content-between">
        <div>
            <div class="mt-36">
                <h2 class="text-gray-50 text-5xl font-light capitalize">Hi, I'm a front-end</h2>
                <h1 class="text-gray-100 text-6xl font-bold capitalize mt-6">Web Developer</h1>
                <p class="text-gray-50 text-xl mt-4">lives in Dhaka, Bangladesh.</p>
            </div>
            <div class="flex items-center mt-10">
                <button class="bg-slate-900 text-gray-50 px-10 py-3 shadow-md">View My Works</button>
                <button class="pl-10 underline hover:no-underline">Contact Me<i class="fa-solid fa-circle-arrow-down ml-2"></i></button>
            </div>
        </div>
        <div class="mt-16">
            <img src="https://scontent.fdac24-5.fna.fbcdn.net/v/t39.30808-6/293301502_1238596496912927_6187896910423254112_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=dtqD3taCK8MQ7kNvgFg3dgW&_nc_ht=scontent.fdac24-5.fna&oh=00_AYD1q0QSe_aeNmYoG1TN0YTXMV6YJkie7_lJObIL0aNpjg&oe=66988035" alt="Samrat Ahmed" class="profile rounded-full bg-white p-4 shadow-lg shadow-gray-400">
        </div>
    </div>
    <!-- Page-1 End -->


    <!-- Page-2 Start -->
    <div class="h-full pb-16 px-28 pt-1.5">
        <div class="flex items-center justify-center mt-20"><p class="text-center bg-rose-500 px-3 py-.5">About Me</p></div>
            <h1 class="text-center text-4xl mt-4 font-semibold">Know Me More</h1>
        <div class="flex place-content-between mt-6">
            <div>
                <h1 class="text-3xl pb-3 mt-6 text-slate-900">Hi, I'm <b class="text-black">Samrat Ahmed.</b></h1>
                <p class="max-w-3xl text-xl leading-9 font-light text-slate-900">I'm an aspiring front-end web developer currently enhancing my skills and knowledge. I've already learned HTML, CSS, and Tailwind CSS, and I'm now diving into JavaScript to further my expertise. My passion lies in creating visually appealing and user-friendly web interfaces, and I'm excited to continue growing and evolving in this dynamic field.</p>
            </div>
            <div>
                <div class="mt-10">
                    <div class="w-32 h-32 rounded-full bg-rose-500 mt-12 ml-10 mb-4">
                        <h1 class="text-center text-9xl text-slate-600">2</h1>
                    </div>
                </div>
                <p class="text-right text-xl">Months of <b>Experience</b></p>
            </div>
        </div>
        <div class="flex items-center place-content-between mt-14">
            <div>
                <p class="text-slate-900 mb-2">Name:</p>
                <P class="font-bold">Samrat Ahmed</P>
            </div>
            <div>
                <p class="text-slate-900 mb-2">E-mail:</p>
                <p class="font-bold">samratahmed11x@gmail.com</p>
            </div>
            <div>
                <p class="text-slate-900 mb-2">Date of Birth:</p>
                <p class="font-bold">26 August, 2004</p>
            </div>
            <div>
                <p class="text-slate-900 mb-2">From:</p>
                <p class="font-bold">Dhaka, Bangladesh</p>
            </div>
        </div>
    </div>
    <!-- Page-2 End -->


    <!-- Page-3 Start -->
    <div class="h-full bg-slate-100 px-28 pt-1 pb-28">


        <!-- Heading Part Start-->
        <div class="flex items-center justify-center mt-20"><p class="text-center bg-rose-500 px-3 py-.5">What I Do?</p></div>
  

```html
<!-- Page-3 Start -->
<div class="h-full bg-slate-100 px-28 pt-1 pb-28">
    <!-- Heading Part Start-->
    <div class="flex items-center justify-center mt-20">
        <p class="text-center bg-rose-500 px-3 py-.5">What I Do?</p>
    </div>
    <h1 class="text-center text-4xl mt-4 font-semibold">How I can help your next project</h1>
    <!-- Heading Part End -->

    <!-- First 3 Services Start -->
    <div class="flex place-content-between mt-16">
        <div>
            <i class="fa-solid fa-palette text-5xl ml-36 mb-4 text-rose-500"></i>
            <h1 class="text-2xl font-medium text-center mb-2">Graphic Design</h1>
            <p class="text-md text-center max-w-80 font-normal text-slate-900">I have experience in graphic design using Canva, creating visually appealing designs and layouts for various projects.</p>
        </div>
        <div>
            <i class="fa-solid fa-desktop text-5xl mb-4 text-rose-500 ml-32"></i>
            <h1 class="text-2xl font-medium text-center mb-2">Web Development</h1>
            <p class="text-md text-center max-w-80 font-normal text-slate-900">As a front-end developer, I build responsive and user-friendly websites using HTML, CSS, Tailwind CSS, and JavaScript.</p>
        </div>
        <div>
            <i class="fa-solid fa-code text-5xl mb-4 text-rose-500 ml-32"></i>
            <h1 class="text-2xl font-medium text-center mb-2">JavaScript Programming</h1>
            <p class="text-md text-center max-w-80 font-normal text-slate-900">I am proficient in JavaScript, enhancing web functionality and user interactivity to create dynamic web applications.</p>
        </div>
    </div>
    <!-- First 3 Services End -->

    <!-- Second 3 Services Start -->
    <div class="flex place-content-between mt-16">
        <div>
            <i class="fa-solid fa-mobile-alt text-5xl ml-36 mb-4 text-rose-500"></i>
            <h1 class="text-2xl font-medium text-center mb-2">Mobile Responsive Design</h1>
            <p class="text-md text-center max-w-80 font-normal text-slate-900">I ensure that all websites are mobile-friendly and optimized for different screen sizes and devices.</p>
        </div>
        <div>
            <i class="fa-solid fa-puzzle-piece text-5xl mb-4 text-rose-500 ml-32"></i>
            <h1 class="text-2xl font-medium text-center mb-2">Problem Solving</h1>
            <p class="text-md text-center max-w-80 font-normal text-slate-900">I enjoy tackling complex problems and finding effective solutions through coding and design.</p>
        </div>
        <div>
            <i class="fa-solid fa-lightbulb text-5xl mb-4 text-rose-500 ml-32"></i>
            <h1 class="text-2xl font-medium text-center mb-2">Creative Ideas</h1>
            <p class="text-md text-center max-w-80 font-normal text-slate-900">I bring innovative ideas to the table, ensuring unique and engaging user experiences.</p>
        </div>
    </div>
    <!-- Second 3 Services End -->
</div>
<!-- Page-3 End -->

</body>
</html>
```
