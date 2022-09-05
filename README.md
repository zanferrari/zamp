# zamp webserver (standalone)
"Zanfi" **Apache** (2.4.39) **MariaDb** (10.4) **Php** (7.4.30 and 8.1.10) webserver

This **webserver** runs as **standalone** in a directory even in a memory thumb. Make a directory put the content in it. This is a development environment. Do not use it for production.

Double click the **zamp.hta** file to start Apache webserver and MySql database server.

"NO" service is installed. You have to start and stop manually the two servers. Windows **firewall** will ask for permissions to allow traffic.

Apache runs behind port 80 and mysql behind 3306.

The document root is {yourDrive}:\{yourCreatedDir}\root.

Open a browser and type localhost. You should get a phpinfo() report.

MySql user is "root" and password is "zamp" (without quotes).

Mail is sent through **Sendmail** (you have to update the .ini file with your credentials)

~~You can modify the settings of the .ini files in:~~

~~Sendmail : {yourDrive}:\{yourCreatedDir}\Sendmail\sendmail.ini

~~Php: {yourDrive}:\{yourCreatedDir}\php\php.ini~~

~~MySql: {yourDrive}:\{yourCreatedDir}\mariadb\my.ini~~

~~Apache: {yourDrive}:\{yourCreatedDir}\Apache24\conf\httpd.conf~~

#### No need to manually set working paths. Launching Apache all working paths should be set automatically

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
