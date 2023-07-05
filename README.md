<div class="ch bg dx dy dz ea"><div class=""><h1 id="b4c1" class="pw-post-title et eu ev be ew ex ey ez fa fb fc fd fe ff fg fh fi fj fk fl fm fn fo fp fq fr fs ft fu fv bj" data-selectable-paragraph="">The ultimate Apex Test Data Factory 🏭👌</h1></button></div></div></div></div></div></div></div></div></div><h1 id="982c" class="km kn ev be ko kp kq kr ks kt ku kv kw kx ky kz la lb lc ld le lf lg lh li lj bj" data-selectable-paragraph="">Overview of Apex Testing</h1><figure class="ln lo lp lq lr ls lk ll paragraph-image"><div class="lk ll lm"><picture><source srcset="https://miro.medium.com/v2/resize:fit:640/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 640w, https://miro.medium.com/v2/resize:fit:720/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 720w, https://miro.medium.com/v2/resize:fit:750/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 750w, https://miro.medium.com/v2/resize:fit:786/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 786w, https://miro.medium.com/v2/resize:fit:828/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 828w, https://miro.medium.com/v2/resize:fit:1100/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 1100w, https://miro.medium.com/v2/resize:fit:472/format:webp/1*lh6DOSkDgNR6drXLEd0sPw.png 472w" sizes="(min-resolution: 4dppx) and (max-width: 700px) 50vw, (-webkit-min-device-pixel-ratio: 4) and (max-width: 700px) 50vw, (min-resolution: 3dppx) and (max-width: 700px) 67vw, (-webkit-min-device-pixel-ratio: 3) and (max-width: 700px) 65vw, (min-resolution: 2.5dppx) and (max-width: 700px) 80vw, (-webkit-min-device-pixel-ratio: 2.5) and (max-width: 700px) 80vw, (min-resolution: 2dppx) and (max-width: 700px) 100vw, (-webkit-min-device-pixel-ratio: 2) and (max-width: 700px) 100vw, 236px" type="image/webp"><source data-testid="og" srcset="https://miro.medium.com/v2/resize:fit:640/1*lh6DOSkDgNR6drXLEd0sPw.png 640w, https://miro.medium.com/v2/resize:fit:720/1*lh6DOSkDgNR6drXLEd0sPw.png 720w, https://miro.medium.com/v2/resize:fit:750/1*lh6DOSkDgNR6drXLEd0sPw.png 750w, https://miro.medium.com/v2/resize:fit:786/1*lh6DOSkDgNR6drXLEd0sPw.png 786w, https://miro.medium.com/v2/resize:fit:828/1*lh6DOSkDgNR6drXLEd0sPw.png 828w, https://miro.medium.com/v2/resize:fit:1100/1*lh6DOSkDgNR6drXLEd0sPw.png 1100w, https://miro.medium.com/v2/resize:fit:472/1*lh6DOSkDgNR6drXLEd0sPw.png 472w" sizes="(min-resolution: 4dppx) and (max-width: 700px) 50vw, (-webkit-min-device-pixel-ratio: 4) and (max-width: 700px) 50vw, (min-resolution: 3dppx) and (max-width: 700px) 67vw, (-webkit-min-device-pixel-ratio: 3) and (max-width: 700px) 65vw, (min-resolution: 2.5dppx) and (max-width: 700px) 80vw, (-webkit-min-device-pixel-ratio: 2.5) and (max-width: 700px) 80vw, (min-resolution: 2dppx) and (max-width: 700px) 100vw, (-webkit-min-device-pixel-ratio: 2) and (max-width: 700px) 100vw, 236px"><img alt="" class="bg lt lu c" width="236" height="205" loading="eager" role="presentation" src="https://miro.medium.com/v2/resize:fit:472/1*lh6DOSkDgNR6drXLEd0sPw.png"></picture></div></figure><p id="8417" class="pw-post-body-paragraph lv lw ev lx b ly lz ma mb mc md me mf mg mh mi mj mk ml mm mn mo mp mq mr ms eo bj" data-selectable-paragraph="">In order to deploy Apex code to production</p><ul class=""><li id="0892" class="lv lw ev lx b ly lz ma mb mc md me mf mt mh mi mj mu ml mm mn mv mp mq mr ms mw mx my bj" data-selectable-paragraph=""><em class="mz">[Required] </em>At least 75% of your Apex code must be covered by unit tests, and all of those tests must pass</li><li id="d8e1" class="lv lw ev lx b ly na ma mb mc nb me mf mt nc mi mj mu nd mm mn mv ne mq mr ms mw mx my bj" data-selectable-paragraph=""><em class="mz">[Required]</em> Every trigger must have some test coverage.</li><li id="987b" class="lv lw ev lx b ly na ma mb mc nb me mf mt nc mi mj mu nd mm mn mv ne mq mr ms mw mx my bj" data-selectable-paragraph=""><em class="mz">[Recommended]</em> Use a test data factory utility</li><li id="5e01" class="lv lw ev lx b ly na ma mb mc nb me mf mt nc mi mj mu nd mm mn mv ne mq mr ms mw mx my bj" data-selectable-paragraph=""><em class="mz">[Recommended] A</em>void using SeeAllData=true</li><li id="c54f" class="lv lw ev lx b ly na ma mb mc nb me mf mt nc mi mj mu nd mm mn mv ne mq mr ms mw mx my bj" data-selectable-paragraph=""><em class="mz">[Recommended]</em> Use the @TestSetup annotation</li></ul><p id="a376" class="pw-post-body-paragraph lv lw ev lx b ly lz ma mb mc md me mf mg mh mi mj mk ml mm mn mo mp mq mr ms eo bj" data-selectable-paragraph="">In order to write tests, you need to generate test data</p><h1 id="d16b" class="km kn ev be ko kp kq kr ks kt ku kv kw kx ky kz la lb lc ld le lf lg lh li lj bj" data-selectable-paragraph="">TestDataFactory to the rescue !</h1><figure class="ln lo lp lq lr ls lk ll paragraph-image"><div role="button" tabindex="0" class="ng nh go ni bg nj"><div class="lk ll nf"><picture><source srcset="https://miro.medium.com/v2/resize:fit:640/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 640w, https://miro.medium.com/v2/resize:fit:720/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 720w, https://miro.medium.com/v2/resize:fit:750/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 750w, https://miro.medium.com/v2/resize:fit:786/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 786w, https://miro.medium.com/v2/resize:fit:828/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 828w, https://miro.medium.com/v2/resize:fit:1100/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 1100w, https://miro.medium.com/v2/resize:fit:1400/format:webp/1*fV06eqirHjmpiZn1ZUPgZg.png 1400w" sizes="(min-resolution: 4dppx) and (max-width: 700px) 50vw, (-webkit-min-device-pixel-ratio: 4) and (max-width: 700px) 50vw, (min-resolution: 3dppx) and (max-width: 700px) 67vw, (-webkit-min-device-pixel-ratio: 3) and (max-width: 700px) 65vw, (min-resolution: 2.5dppx) and (max-width: 700px) 80vw, (-webkit-min-device-pixel-ratio: 2.5) and (max-width: 700px) 80vw, (min-resolution: 2dppx) and (max-width: 700px) 100vw, (-webkit-min-device-pixel-ratio: 2) and (max-width: 700px) 100vw, 700px" type="image/webp"><source data-testid="og" srcset="https://miro.medium.com/v2/resize:fit:640/1*fV06eqirHjmpiZn1ZUPgZg.png 640w, https://miro.medium.com/v2/resize:fit:720/1*fV06eqirHjmpiZn1ZUPgZg.png 720w, https://miro.medium.com/v2/resize:fit:750/1*fV06eqirHjmpiZn1ZUPgZg.png 750w, https://miro.medium.com/v2/resize:fit:786/1*fV06eqirHjmpiZn1ZUPgZg.png 786w, https://miro.medium.com/v2/resize:fit:828/1*fV06eqirHjmpiZn1ZUPgZg.png 828w, https://miro.medium.com/v2/resize:fit:1100/1*fV06eqirHjmpiZn1ZUPgZg.png 1100w, https://miro.medium.com/v2/resize:fit:1400/1*fV06eqirHjmpiZn1ZUPgZg.png 1400w" sizes="(min-resolution: 4dppx) and (max-width: 700px) 50vw, (-webkit-min-device-pixel-ratio: 4) and (max-width: 700px) 50vw, (min-resolution: 3dppx) and (max-width: 700px) 67vw, (-webkit-min-device-pixel-ratio: 3) and (max-width: 700px) 65vw, (min-resolution: 2.5dppx) and (max-width: 700px) 80vw, (-webkit-min-device-pixel-ratio: 2.5) and (max-width: 700px) 80vw, (min-resolution: 2dppx) and (max-width: 700px) 100vw, (-webkit-min-device-pixel-ratio: 2) and (max-width: 700px) 100vw, 700px"><img alt="" class="bg lt lu c" width="700" height="272" loading="lazy" role="presentation" src="https://miro.medium.com/v2/resize:fit:1400/1*fV06eqirHjmpiZn1ZUPgZg.png"></picture></div></div></figure><blockquote class="nk nl nm"><p id="cd48" class="lv lw mz lx b ly lz ma mb mc md me mf mt mh mi mj mu ml mm mn mv mp mq mr ms eo bj" data-selectable-paragraph="">The ultimate Apex Test Data Factory</p></blockquote><p id="ccd4" class="pw-post-body-paragraph lv lw ev lx b ly lz ma mb mc md me mf mg mh mi mj mk ml mm mn mo mp mq mr ms eo bj" data-selectable-paragraph=""><a class="af nn" href="https://github.com/OYF-Ltd/TestDataFactory" rel="noopener ugc nofollow" target="_blank">TestDataFactory</a> is an Apex Test Data Factory that uses the <a class="af nn" href="https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_dynamic_describe_objects_understanding.htm" rel="noopener ugc nofollow" target="_blank">Apex Describe Information</a> to automatically detect and auto-fill all the required fields of an sObject</p><p id="a264" class="pw-post-body-paragraph lv lw ev lx b ly lz ma mb mc md me mf mg mh mi mj mk ml mm mn mo mp mq mr ms eo bj" data-selectable-paragraph="">Features of the Test Data Factory <a class="af nn" href="https://github.com/OYF-Ltd/TestDataFactory" rel="noopener ugc nofollow" target="_blank"><strong class="lx ew">TestDataFactory</strong></a></p><ol class=""><li id="8dd4" class="lv lw ev lx b ly lz ma mb mc md me mf mt mh mi mj mu ml mm mn mv mp mq mr ms no mx my bj" data-selectable-paragraph=""><strong class="lx ew">Auto</strong>-detect all the required fields of an sObject and <strong class="lx ew">auto</strong>-assign them <strong class="lx ew">auto</strong>-generated default values</li><li id="5dad" class="lv lw ev lx b ly na ma mb mc nb me mf mt nc mi mj mu nd mm mn mv ne mq mr ms no mx my bj" data-selectable-paragraph=""><strong class="lx ew">Auto</strong>-detect all the required lookup fields of an sObject and <strong class="lx ew">auto</strong>-create the related sObjects and applies the feature 1</li></ol><h1 id="1f6b" class="km kn ev be ko kp kq kr ks kt ku kv kw kx ky kz la lb lc ld le lf lg lh li lj bj" data-selectable-paragraph="">Examples</h1><h2 id="0d25" class="np kn ev be ko nq nr ns ks nt nu nv kw mg nw nx ny mk nz oa ob mo oc od oe of bj" data-selectable-paragraph=""><strong class="al">1- Create an sObject</strong></h2>

```apex
  Contact con = (Contact)TestDataFactory.createSObject('Contact');
```

<h2>2- Create a Contact by providing a map to assign values to fields in the main and the related sObjects</h2>

You can assign values to the main sObject or any related sObject, all sObjects will be created with the required fields auto-filled


```apex
  Contact con = (Contact)TestDataFactory.createSObject('Contact', new Map<String,Object>{
  'FirstName' => 'Doe',
  'LastName' => 'John',
  'Account.Description' => 'Description of the related account',
  'Account.Parent.Name' => 'Name of the parent Account'
});
```

<h2>3- Auto-generate values for non required fields</h2>

You can auto-generate a value for a non required field by assigning the TestDataFactory.DEFAULT_VALUE to it, in the Map of values

```apex
  Contact con = (Contact)TestDataFactory.createSObject('Contact', new Map<String,Object>{
  'Description' => TestDataFactory.DEFAULT_VALUE,
  'Account.Phone' => TestDataFactory.DEFAULT_VALUE
});
```


<h2>4- Force the instantiation of a related sObject</h2>

For example when creating a Contact you can force the Test Data Factory to create a related Account, even if an Account is not required

```apex
  Contact con = (Contact)TestDataFactory.createSObject('Contact', new Map<String,Object>{
  'AccountId' => TestDataFactory.DEFAULT_VALUE
});
```

<h2>5- Provide an Id for a required related sObject to avoid its instantiation</h2>

You can provide an Id for a required related sObject, to force the use of that Id and prevent the instantiation of the related sObject

```apex
  User u = (User)TestDataFactory.createSObject('User', new Map<String,Object>{
  'ProfileId' => UserInfo.getProfileId()
});
```

<h2>6- Provide a map for a related sObject</h2>

You can provide a sub map of values for a related sObject

```apex
    Contact con = (Contact)TestDataFactory.createSObject('Contact', new Map<String,Object>{
  'Description' => 'Contact description',
  'Account' => new Map<String,Object>{
    'Name' => 'Account Name',
    'Description' => 'Account Description'
  }
});
```
<h2>7- Create and insert a list of Contact sObjects</h2>

Create & insert 10 contacts

```apex
  List<Contact> conList = TestDataFactory.createSObjectList('Contact',10);
```
<h2>8- Create and insert a list of users using the index merge value</h2>

The following code creates 10 users with different usernames and nicknames

```apex
  List<User> uList = TestDataFactory.createSObjectList('User', new Map<String,Object>{
  'ProfileId' => UserInfo.getProfileId(),
  'Username' => 'test{!index}@mytestdomain.developer',
  'CommunityNickname' => 'test{!index}'
},10);
```
<h2>9- Create 5 Accounts with different names</h2>

Create a list of 5 Account sObjects with different names and a same description

```apex
  List<Account> accList = TestDataFactory.createSObjectList('Account', new Map<String,Object>{
  'Name' => new List<String>{'Google','Amazon','Facebook','Apple','Microsoft'}
  'Description' => 'Same description'
},5);
```
<h2>10- Create 10 Cases related to 10 Accounts</h2>

Create a list of Acount sObjects and link them to a list of 10 Case sObjects

```apex
  List<Account> accList = TestDataFactory.createSObjectList('Account', new Map<String,Object>{
  'Description' => 'Account Description'
},10);

List<Case> caseList = TestDataFactory.createSObjectList('Case', new Map<String,Object>{
  'Account' => AccList,
  'Contact.Account' => AccList
},10);
```
