# JS_Project_3-chromeExtension

Deployment:

1. In browser type <edge://extensions/>

2. Open developer mode

3. Load Unpacked and select the path to this folder


## Thought Process:

### Function Needed:
1. render(leads)
2. inputBtn.addEventListener()
    - Save the input value to the lead array
    - Clear the input field
    - Put the array into local storage (stringify)
    - call render() function
3. deleteBtn.addEventListener()
    - Clear local storage
    - Clear lead array
    - call render() function

4. tabBtn.addEventListener()
    - Save the current tab to the lead array
    - Put the array into local storage (stringify)
    - call render() function


### Lessons Learnt:
1. addEventListener()
2. innerHTML
3. input.value
4. template strings
5. localStorage
  >- JSON.stringify()
  >- JSON.parse()
6. manifest
