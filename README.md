# ceedling_header_parsing_patch

### If you attempt to mock functions which take a multidimensional array as a parameter in Ceedling, you will likely encounter the error raised in this [CMock Issue](https://github.com/ThrowTheSwitch/CMock/issues/213). 

<p>To address this, navigate to the ceedling directory within your Ruby installation:
<br>Ruby27-x64\lib\ruby\gems\2.7.0\gems\ceedling-0.31.0\vendor\cmock\lib (note: version number may vary). 
<br><br>Replace the 'cmock_generator.rb' and 'cmock_header_parser.rb' with the versions attached in this repository.
<br><br>Run 'ceedling test:all' to ensure your unit tests compile successfully after these changes.<\p>
