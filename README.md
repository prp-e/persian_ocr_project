# Persian OCR Project

This repository is my biggest [FLOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) project. I had it in my mind since the last year, when I was working on an _automatic license plate number recognition_ project. So what I was thinking of was this _a big FLOSS project_ and then, the idea of an OCR project came to my mind as well. 

Now I started working on the whole idea and this repository will be updated for every phase of the project.

## Important Notes

## Project Technical Details

- Programming Language: Python 3 (3.9 on local machine, remote machines depend on where we do our tasks)
- AI library: PyTorch
- Model: [YOLOv5](https://github.com/ultralytics/yolov5)

## Project Phases

This part has been divided to two. First part is mostly considered _lab phase_ since we're working as a group of data scientists and AI enthusiasts to develop and deploy our model and the second part is also considered as _business/product phase_ and we try to present the result as a product to the outside world. 

### Lab phases

- Number recognition
    - [ ] Data generation using [Zarnevis](https://github.com/prp-e/zarnevis).
    - [ ] Training YOLOv5 on generated data.
    - Testing the result.
        - [ ] Test on different numbers written on the same fonts.
        - [ ] Test on same or different numbers written in different fonts.
        - [ ] Test on hand-written numbers to find out how accurate our model is.
    - [ ] Asking participants to write down some random numbers (Data generation for hand-written numbers)
    - [ ] Training YOLOv5 on both hand-written and digital numbers.
    - Final Tests
        - [ ] Test on different numbers, both hand-written and digital.
- Letter recognition
- Word detection
- Jupyter notebook for people who want to test the model. 
### Business/Product phases