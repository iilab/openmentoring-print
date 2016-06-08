
## Encrypting your Facebook instant messages

# Step 1: Open security settings
Select **Tools &gt; Options** from the Jitsi menu and subsequently select the **Security** tab and its **Chat** sub-tab. You will then see a window similar to one shown in the image below:

![](jitsi-en-win-35.png)
&lt;br&gt;
# Step 2: Generate a key
Click on the **&quot;Generate&quot;** button. As a result you will see the fingerprint of the key that has been generated:

![](jitsi-en-win-36.png)
&lt;br&gt;
One key is generated for each account. You only need to do this again if you add a new account or install Jitsi on another device and do not move the existing keys to it.
&lt;br&gt;
You are now ready to communicate:
&lt;br&gt;
# Step 3: Open a new chat
Select a contact from the Jitsi main window and click on the *send message icon* (first from the left under the contact&#39;s name) to open a text chat window:

![](jitsi-en-win-37.png)
&lt;br&gt;
Note the Encrypt chat with OTR icon, the open padlock on the right-top side of the window. This inconspicuous symbol informs you whether the chat is encrypted or not. Now the lock is open (there is a tiny space between handle and the body of the lock!).
&lt;br&gt;
# Step 4: Encrypt the chat
Click on the Encrypt chat with OTR icon. Note the changes in the window:
![](jitsi-en-win-38.png)

Observe that the padlock is now locked. This means that whatever messages you and your contact send to each other are encrypted. Note the message that this is an unverified private conversation and that you should authenticate your contact.
&lt;br&gt;
# Step 5: Authenticate contact
Click on the link authenticate sally.the.doer@jit.si to open the Authenticate Buddy window:

![](jitsi-en-win-39.png)
&lt;br&gt;
Note the message that encourages you to compare the fingerprints of your keys with your contact over another channel (not this text chat). In doing this, you can be more certain that you are communicating with your contact and not somebody else.
&lt;br&gt;
A good choice for key comparisons is to do it face to face, or via video or voice communication as these provide easier means to authenticate the identity of the other person.
&lt;br&gt;
After you compare fingerprints, select the option I have verified the fingerprint from the pull-down menu and click on Authenticate Buddy:
![](jitsi-en-win-40.png)
&lt;br&gt;
Closing the Authenticate Buddy window returns you to the chat window:

![](jitsi-en-win-41.png)
&lt;br&gt;
Note that padlock no longer includes the orange triangle with the white exclamation mark. This means that you have authenticated your contact.
&lt;br&gt;
The authentication should be done only once per contact. If the triangle with exclamation mark returns, it means that you are chatting to somebody who you have not yet authenticated.
&lt;br&gt;
This can happen when your contact moves to another device with another encryption key (another installation of Jitsi, or another OTR enabled program, etc.). In this case you will need to re-authenticate each other again to be sure of the identity of person with whom you communicate.
