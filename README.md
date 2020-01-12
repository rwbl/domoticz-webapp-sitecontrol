# Web App Site Control (WASC)
Web based GUI, using Node-RED, to control a Domoticz Home Automation System with connected hardware.
Part of the Domoticz Home Automation Workbook by the author.

### Purpose
To control the Domoticz Home Automation System, running on a Raspberry Pi, via a browser-based application (WebUI, built with Node-RED).

* Easy-to-use User Interface accesible from any device capable running a browser (smartphones, tablets, PC, SBC, TV)
* Control heating (HomematicIP) & lights (Philips Hue)
* Information only for weather data, key dates and status postbox

The goal has been to develop a prototype first, i.e. workout the concept with initial functionalitz, to be able to enhance or modify the application further.
This solution is also ment as a trigger for ideas or as a suggestion building an alternate GUI (WebUI) to access the Domoticz Homeautomation System.

The User Interface is translated to the German language.

Screenshot, from an Android device, with additional information of the various functions. 
![wasc-ui](https://user-images.githubusercontent.com/47274144/72217110-576ed000-352a-11ea-9857-3a41667dd50f.png)

The communication concept with HTTP API requests between Node-RED and Domoticz.
![wasc-communication](https://user-images.githubusercontent.com/47274144/72217109-550c7600-352a-11ea-91f2-f87c98e709cf.png)

### Notes
In the mean time, after having used the application for a while, it has become the main application to access the (our) Domoticz Home Automation system from various devices.

The application is rather tailer made.
If want to use for own purposes, it will need a deep dive into the solution, which is based on Node-RED and JavaScript (used in the many function nodes).
The flows are commented, so recommend to checkout.
In this document, the flows are described more at higher level.

It is not the intention to explain Node-RED in great detail.
Visit the [Node-RED website](https://nodered.org/) to explore more.
The author is also on a steep learning curve on how to develop Node-RED solutions.
This means, there might be better ways to accomplish a function, but so far this solution is working fine.

The solution is being developed further but this documentation might not be up-to-date. Check out the comments in the flows.

### Documentation
The PDF document *domoticz-webapp-sitecontrol.pdf* describes the solution and the concept.

### Credits
To the developers of Domoticz and Node-RED and to all sharing related information.
Without these, it would not be possible to build this project and write the workbook.

### Disclaimer
THIS DOCUMENT IS PROVIDED BY THE AUTHOR “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
