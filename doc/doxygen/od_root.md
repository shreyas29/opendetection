Open Detection {#mainpage}
==============


Open Detection
====


\htmlonly
<div class="container-fluid">
<div class="row">
    <div class="col-sm-6">
\endhtmlonly
    
**Open Detection (OD)** is a standalone open source project for object detection and recognition in images and 3D point clouds. Open Detection is released under the terms of the **BSD license**, and thus free for commercial and research use. The project was originated under **Google Summer of Code 2015**  with the aim of having a vision tool for robotics (in particular for [Robocomp](https://github.com/robocomp/robocomp)). 

The library is built with a very specific goal - to answer the fundamental problem of Computer Vision - Object Recognition and Detection. We make available to everyone the existing solution in this direction in a common, intuitive and user-friendly APIs. Our simple and user-friendly APIs make this a great tool for **Robotics Applications and robots** and **Computer Vision beginners and enthusiasts**. And of course, the method dependent parameters to fine-tune detections to the limit, makes this a great tool for **Computer Vision researchers and experts**.   

##Getting Started
* Download and compile using \ref installation_instruction
* The \ref getting_started guide
* Go through the \ref tutorial_root "User Manual"
* Learn the \ref basic_structures and pipeline
    
##Quick Links
- <a href="annotated.html"><b>API Documentation</b></a>
- Source Code: https://github.com/krips89/opendetection
- Queries: mailto:kripasindhu.sarkar@dfki.de     
- Discussion group: https://groups.google.com/forum/#!forum/opendetection/   
    
##New: GSoC 2016 Ideas
**We are in!**

We are selected in Google Summer of Code 2016 as a mentoring organization!  We hope we can make maximum out of it and get great contributions from the students. Please find the list of ideas for GSoC here - \ref idea_list_gsoc2016 "GSoC 2016 Ideas".
        
\htmlonly
    </div>
  <div class="col-sm-6" >
<div class="odlCarouselClass">
  <div id="odlCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#odlCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#odlCarousel" data-slide-to="1"></li>
      <li data-target="#odlCarousel" data-slide-to="2"></li>
      <li data-target="#odlCarousel" data-slide-to="3"></li>
    </ol>
    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      
      <div class="item active">
        <img src="odlogo_detailed.png">
      </div>
      
      <div class="item">
        \endhtmlonly
        \link detection_2d
        \htmlonly
        <img src="snap_hog3.png">         
        <div class="carousel-caption">
          <h4>HOG based detector</h4>          
        </div>
        \endhtmlonly
        \endlink
        \htmlonly
      </div>
           
      <div class="item"> 
        \endhtmlonly
        \link od::l2d::ODCADRecognizer2DLocal
        \htmlonly
        <img src="cadrecog2d.png">        
        <div class="carousel-caption">
          <h4>CAD Recognizer 2D</h4>
          <p>Recognize 3D CAD models from a single 2D image!</p>
        </div>
        \endhtmlonly
        \endlink
        \htmlonly
      </div>
      
      <div class="item">
        \endhtmlonly
        \link detection_3d
        \htmlonly
        <img src="cadrecog3d.png">
        <div class="carousel-caption">
          <h4>CAD Recognizer 3D</h4>
          <p>Recognize/Detect 3D CAD models in Point Cloud from Kinect</p>
        </div>
        \endhtmlonly
        \endlink
        \htmlonly        
      </div> 
            
      <div class="item">
        \endhtmlonly
        \link od::g2d::ODCascadeDetector
        \htmlonly
        <img src="face_business.jpg">
        <div class="carousel-caption">
          <h4>Cascade Classifier and Face Recognizer</h4>    
          <p>Detect face and other objects using Cascade Classifier</p>
        </div>
        \endhtmlonly
        \endlink
        \htmlonly          
      </div>      
      
    </div>
    <!-- Controls -->
    <a class="carousel-control left" href="#odlCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
    </a>
    <a class="carousel-control right" href="#odlCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
    </a>
  </div>
</div>

<div align="center" class="youtubevideo">
    <iframe src="https://www.youtube.com/embed/sp8W0NspY54" frameborder="0" allowfullscreen></iframe>
</div>

   
  
    </div>
    </div>
    

   


  </div>
</div>


\endhtmlonly


