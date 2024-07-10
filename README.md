

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project  
   Convert multiple Videos Shot into single 360 panoramic Image using openCV image stitching.
[![VideoTo360Panorama][product-screenshot]](resources/startpage.PNG)
[![Page1][product-screenshot1]](resources/page1.PNG)



### Built With

* [Python 3.9.5]()
* [OpenCv 4.5.2]()
* [Tkinter]()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is  list of python packages you need to use the software and how to install them.
* pip
  ```sh
   pip install opencv-contrib-python
   pip install pillow
   pip install matplotlib
   pip install imutils
  
  python viewer.py
  ```

<!-- USAGE EXAMPLES -->
## Usage

1. Select 3 short video files
2. Set the number of frames you want to skip
3. Click on "next"
4. You can view the console for which frames are being picked and which ones are deleted for being blurred
5. output is stored in output directory


<!--OUTPUT-->
[![Output][output]](output/result.jpg)





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



[product-screenshot]: resources/startpage.PNG
[output]: output/result.jpg
