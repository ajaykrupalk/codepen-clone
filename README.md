# CodePen Clone using ReactJS

<h3>Challenges faced</h3>
- CodeMirror 5.65.8 had to be used due to dependency resolving issues

<h3>How was this project built?</h3>
- First, the layout for the page was built
- Divided the whole page into two
- Top pane is used for the code editors
- Bottom pane is used for the output of the code
- In the below pane we use an iframe to display the output
- iframe has attributes like srcDoc to show the output
- sandbox to allow scripts
- Top Pane uses a custom component called Editor
