THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

=============================
ILIAS Example Question Plugin
=============================

Author:   Fred Neumann <fred.neumann@fau.de>
Version:  1.0.2 (2015-02-19)
Supports: ILIAS 4.4.3 - 5.0

Installation
------------

1. Copy the assExampleQuestion directory to your ILIAS installation at the following path 
(create subdirectories, if neccessary):
Customizing/global/plugins/Modules/TestQuestionPool/Questions/assExampleQuestion

2. Go to Administration > Plugins

3. Choose "Update" for the assExampleQuestion plugin
4. Choose "Activate" for the assExampleQuestion plugin
5. Choose "Refresh" for the assExampleQuestion plugin languages

There is nothing to configure for this plugin.

Usage
-----

This is a minimalistic example for question type plugins of ILIAS. 
Its intention is to document the plugin slot and test its API.
It has the minimum set of classes and methods needed for question type plugins.
It adds no extra table to the database.

===============
Version History
===============

Version 1.0.2 (2015-02-19)
--------------------------
* new version for ILIAS 5.0

Version 1.0.0
-------------
* Initial version for ILIAS 4.4.3