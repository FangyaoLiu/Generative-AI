Project Summary

In this project I am going to build a little app that allows users to select a subject and then change its background, OR keep the background and change the subject. To be specific:

* Utilize Facebook's SAM (Segment Anything Model) to create a mask around the selected object.
* The user is shown this result to either accept it or refine the mask further with additional points.
* Crop the selected area.
* Use stable-diffusion model to impaint cropped area based on user text input.
