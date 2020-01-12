# Web App Site Control (WASC)
Web based GUI, using Node-RED, to control a Domoticz Home Automation System with connected hardware.
Part of the Domoticz Home Automation Workbook by the author.

### Purpose
To control the Domoticz Home Automation System, running on a Raspberry Pi 3B+, via a browser-based application (WebUI, built with Node-RED).

* Easy-to-use User Interface accesible from any device capable running a browser (smartphones, tablets, PC, SBC, TV)
* Control heating (HomematicIP) & lights (Philips Hue)
* Information only for weather data, key dates and status postbox

The goal has been to develop a Node-RED prototype first, i.e. workout the concept with initial functionality, to be able to enhance or modify the application further.
_This solution is also ment as a trigger for ideas or as a suggestion building an alternate GUI (WebUI) to access the Domoticz Homeautomation System._

The WebUI is translated into German.

**Screenshots**, from an Android device, with additional information of the various functions. 
![wasc-ui](https://user-images.githubusercontent.com/47274144/72217193-74f06980-352b-11ea-9eb9-80437d275bd7.png)

**Communication concept** with HTTP API requests between Node-RED and Domoticz.
![wasc-communication](https://user-images.githubusercontent.com/47274144/72217198-889bd000-352b-11ea-83b3-205ac32fef02.png)
_Note:_ Not all functions displayed.

### Notes
In the mean time, after having used the application for a while, it has become the _main application to access_ the (our) Domoticz Home Automation system from various devices.

The application is rather _tailer made_ and has ~100 nodes.
If want to use for own purposes, it will need a deep dive into the solution, which is based on Node-RED and JavaScript (used in the many function nodes).
The flows are commented, so recommend to checkout.

**Screenshot** of the flow just as an illustration. Read more in the PDF document.
![wasc-flowsillustration](https://user-images.githubusercontent.com/47274144/72219317-1cc66100-3545-11ea-9290-d938f4772926.png)

It is not the intention to explain Node-RED in great detail.
Visit the [Node-RED website](https://nodered.org/) to explore more.
The author is also on a steep learning curve on how to develop Node-RED solutions.
This means, there might be better ways to accomplish a function, but so far this solution is working fine.

The solution is being _developed further_ but this documentation might not be up-to-date. Check out the comments in the flows.

### Documentation
The PDF document **domoticz-webapp-sitecontrol.pdf** describes the solution and the concept.
The files starting with **wasc** contains the Node-RED flows & subflows (formatted). Use the Node-RED import function to import as new flow.

### Software Versions
Linux: 4.19.66-v7+ #1253, Domoticz: 4.10717, Node-RED: 1.0.3 Node-RED Dashboard: 2.19.3

### Credits
To the developers of Domoticz and Node-RED and to all sharing related information.
Without these, it would not be possible to build this project and write the workbook.

### Disclaimer
THIS DOCUMENT IS PROVIDED BY THE AUTHOR “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
