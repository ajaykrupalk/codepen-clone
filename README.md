# CodePen Clone using ReactJS

<h3>Challenges faced</h3>
- CodeMirror 5.65.8 had to be used due to dependency resolving issues

<h3>How was this project built?</h3>

<ul>
<li> First, the layout for the page was built
<li> Divided the whole page into two
<li> Top pane is used for the code editors
<li> Bottom pane is used for the output of the code
<li> In the below pane we use an iframe to display the output
<li> iframe has attributes like srcDoc to show the output
<li> sandbox to allow scripts
<li> Top Pane uses a custom component called Editor
<li> Editor receives attributes language, displayName, value, onChange
<li> Use Controlled component from codemirror-react2 library
</ul>
