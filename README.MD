<img src="assets/bcny_logo.jpg" width="50%" style="border-radius:1em; display: block; margin-left: auto; margin-right: auto;">
<h1>The Browser Company of New York</h1>

<table>
    <tr>
        <td style="width:80%;">
            <h2>Welcome to Python interview environment prep!</h2>
            Thank you for your interest. This is meant to prepare your environment prior to your coding exercise. 
        </td>
        <td style="width:10%">
            <img src="assets/arc_logo.jpg" width="100%" style="border-radius:1em; display: block; margin-left: auto; margin-right: auto;">
        </td>
        <td style="width:10%">
            <img src="assets/python_logo.jpg" width="100%" style="border-radius:1em; display: block; margin-left: auto; margin-right: auto;">
        </td>
    </tr>
</table>

<h2>Requirements</h2>
<ul>
    <li>Latest Python 3 installed. Get it <a href="https://www.python.org/downloads/">here</a></li>
    <li>Download or clone this repo.</li>
</ul>

<h2>Optional</h2>
<ul>
    <li>Your choice of IDE.</li>
</ul>


<h2>Environment prep</h2>
<ol>
    <li>Launch command line terminal <code>win+r</code> then <code>cmd.exe</code> or launch Terminal in macOS.</li><br>
    <li>Enter where this directory is located <code>cd path\to\dir\bcny-interview-python </code></li><br>
    <li>
        Verify Python is installed<br>
        <b>Windows Example:</b>
        <pre><code>C:\bcny-interview-python> python --version<br>
Python 3.12.3</code></pre>
        * Note that your environment command may be <code>python3 --version</code> instead.
    </li><br>
    <li>
        Create a virtual environment<br>
        <b>Windows Example:</b>
        <pre><code>C:\bcny-interview-python> python -m venv .venv</code></pre>
    </li><br>
    <li>
        Enter the virtual environment<br>
        <b>Windows Example:</b>
        <pre><code>C:\bcny-interview-python> C:\bcny-interview-python\.venv\Scripts\activate</code><br>(venv) C:\bcny-interview-python></pre>
        If you've opened PowerShell instead of Windows command line, you can enter venv this way:<br>
        <b>Windows PowerShell Example:</b>
        <pre><code>C:\bcny-interview-python> .\.venv\Scripts\activate<br>
(venv) C:\bcny-interview-python></code></pre>
        <b>Linux / macOS Example:</b>
        <pre><code> ~/bcny-interview-python$ .venv/bin/activate<br>
(venv) bcny-interview-python$</code></pre>
    </li>
    <li>
        Verify Python can run<br>
        <b>Windows Example:</b>
        <pre><code>(venv) C:\bcny-interview-python> python hello_world.py<br>
Hello Arc!</code></pre>
        <b>Linux / macOS Example:</b>
        <pre><code>(venv) bcny-interview-python$ python hello_world.py<br>
Hello Arc!</code></pre>
    </li>
</ol>


<h2>PyCharm setup</h2>
<ol>
    <li>Download and install Pycharm <a href="https://www.jetbrains.com/pycharm/download">here</a></li><br>
    <li>Launch PyCharm</li><br>
    <li>Select <code>Open</code><br><img src="assets/pycharm_1.jpg" width="50%" style="border-radius:1em"></li>
    <li>Navigate to the downloaded <code>bcny-interview-python</code> folder and open it.</li><br>
    <li>Click on the file <code>hello_world.py</code> in the Sidebar<br><img src="assets/pycharm_3.jpg" width="25%" style="border-radius:1em"></li><br>
    <li>Click on top corner run menu and select <code>Edit Configurations...</code><br><img src="assets/pycharm_2.jpg" width="25%" style="border-radius:1em"></li><br>
    <li>Click the plus button <code>+</code> and choose <code>Python</code><br><img src="assets/pycharm_5.jpg" width="25%" style="border-radius:1em"></li><br>
    <li>Enter <code>hello_world</code>as name, verify Run is on the Python venv that was created earlier, script is set to the <code>hello_world.py</code> path and working directory is set to the current directory. Press <code>OK</code><br><img src="assets/pycharm_4.jpg" width="75%" style="border-radius:1em"</li><br>
    <li>Click the green play button. Verify script is run and <code>Hello Arc!</code> is printed<br><img src="assets/pycharm_6.jpg" width="50%" style="border-radius:1em"></li><br>
</ol>


