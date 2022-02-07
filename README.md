# Frontendmentor.io Color Helper
Python script to extract colors from frontendmentor.io to css variables
to run it:
```lang=bash
python main.py your_path_to_style-guide.md
```
example running it aginst the `style-guide.md` file in this repo will output the following:
```lang=css
:root {
    --moderateBlue: hsl(238, 40%, 52%);
    --softRed: hsl(358, 79%, 66%);
    --lightGrayishBlue: hsl(239, 57%, 85%);
    --paleRed: hsl(357, 100%, 86%);
    --darkBlue: hsl(212, 24%, 26%);
    --grayishBlue: hsl(211, 10%, 45%);
    --lightGray: hsl(223, 19%, 93%);
    --veryLightGray: hsl(228, 33%, 97%);
    --white: hsl(0, 0%, 100%);
}
```