# Firebase Setup

### All the data is stored in Firebase  Realtime Database and Firestore database.

In Firebase we store the information about the app, like colors, navigation etc..

And in Firestore is where our actual data is. Like menu content, categories, orders etc..

Let's get started. Create an account in Firebase with your google account.

#### Follow all the guides in the tabs. 

{% tabs %}
{% tab title="Create Project" %}
[Open Firebase](https://firebase.google.com) and Click on "Add Project". 

Accept terms, and create the project.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2814%29.png)
{% endtab %}

{% tab title="Create Realtime DB" %}
Go to Database and then click on the button called "Create database".

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2816%29.png)

After clicking on the button it should appear a window that will ask you about security rules. Click on the Start in **test mode** and after that click **Enable.**

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2811%29.png)

But for production, this is a good starting point. This will allow edit and write to all registered users.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2812%29.png)

```text
{  
  "rules": {  
    ".read": true,  
     ".write": "auth !== null"  
  }  
} 
```
{% endtab %}

{% tab title="Create Firestore DB" %}
Go in Databases -&gt;Cloud Firestore

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%282%29.png)

or

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%284%29.png)

Then, a pop up will appear.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2813%29.png)

For now, use Start in test mode.
{% endtab %}

{% tab title="Create Firestorage" %}
Firebase Storage by default is not initialized. You will need to click on "Storage" and active the Firestorage Bucket.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%289%29.png)

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru.png)
{% endtab %}

{% tab title="Authentication" %}
Go into Firebase console and click on **Authentication** and after that click on **Set up sign-in method.**

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%287%29.png)

Click on **Email/Password** and enable them and click Save.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%288%29.png)

Now click on **Users** and now you should be able to click on **Add user**.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2810%29.png)

Enter your email and password click Add user.
{% endtab %}

{% tab title="Google Login" %}
**I**f you want to allow Google authentication, you have to do is to enable the Google Auth Provider as on the image below.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%286%29.png)

Next, scroll below and there you should add your authorized domain. Place where the Google Login will be performed.

![](../.gitbook/assets/orqmie1lc2wwzkqkwpmaij8a5uz1lewsicncvyru%20%2817%29.png)
{% endtab %}
{% endtabs %}







