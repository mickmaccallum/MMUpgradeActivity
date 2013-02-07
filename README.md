MMUpgradeActivity
===================

This project contains a subclass of UIActivity that allows you to simply pass the App Store ID of the "Pro/+" version of your app to the activity, and when you add it to a UIActivityViewController there will now be a "Upgrade" activity in your activity view controller.

To use this subclass, simply add "MMUpgradeActivity.h" and "MMUpgradeActivity.m" to your project. Make sure that both the "copy file" and "add to target" check boxes are selected.

From there, import "MMUpgradeActivity.h" into your view controller and create an instance of the activity with the following.

```MMUpgradeActivity *upgrader = [MMUpgradeActivity new];
```[upgrader setAppStoreAppID:538725002];```
```[upgrader setTitleOfActivity:@"Go Pro!"];```


//    [upgrader setIconOfActivity:[UIImage imageNamed:@"myOtherImage"]];


^^Optional: If you want to use the images provided with the project, leave that line commented and include the images from this project in yours. If you wish to use your own image, use the line above to add it to the activity.

For a full usage example see the ViewController.m file inside the project.


Created by Michael MacCallum on 2/5/13. 

This Software is provided on an "AS IS" basis. I MAKE NO WARRANTIES, EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION THE IMPLIED WARRANTIES OF NON-INFRINGEMENT, MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, REGARDING THE SOFTWARE OR ITS USE AND OPERATION ALONE OR IN COMBINATION WITH YOUR PRODUCTS.

IN NO EVENT SHALL I BE LIABLE FOR ANY SPECIAL, INDIRECT, INCIDENTAL OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) ARISING IN ANY WAY OUT OF THE USE, REPRODUCTION, MODIFICATION AND/OR DISTRIBUTION OF THE SOFTWARE, HOWEVER CAUSED AND WHETHER UNDER THEORY OF CONTRACT, TORT (INCLUDING NEGLIGENCE), STRICT LIABILITY OR OTHERWISE, EVEN IF I HAVE BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

That being said, you are free to use this code free of charge for absolutely anything you want. You may use this in personal projects, commercial projects or for anything else.

Accreditation is not required, but is always appreciated.