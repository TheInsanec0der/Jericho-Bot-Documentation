---
description: >-
  Wanna Hear Music of your Choice ? Wanna Hear Some Radio 24/7 ? Jericho is
  there for you .
---

# Entertainment

## 🎶 24/7 Music Player

Jericho will Sing many `Songs/Playlists` from Youtube or Spotify with ease and Stage Channel is also Supported with it .

{% tabs %}
{% tab title="Play a Song" %}
```text
dc!music play <Song/Playlist - Name/Link>
```
{% endtab %}

{% tab title="Stop in Music Player" %}
```
dc!music <stop> <force/Blank>
```
{% endtab %}

{% tab title="Skip in Music Player" %}
```
dc!music skip <position/blank> <force/blank>
```
{% endtab %}

{% tab title="Search in Youtube" %}
```
dc!music search <Song-Name>
```
{% endtab %}

{% tab title="Save Songs in Current Track" %}
```
dc!music fav <blank/queue>
```
{% endtab %}

{% tab title="Play Songs in Saved List" %}
```
dc!music fav play <Song ID/all>
```
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
**Position means the Track Number at Queue and can be found by -** **`dc!music queue`**
{% endhint %}

![Glimpse of Stage-Channel Support](../.gitbook/assets/1%20%281%29.png)

### 💫 Music Player \(Without logging Feature\)

💨 This section is very simple if you just want to play a `single song or a playlist`.   
💨 It plays music from YouTube with the support of links from `Spotify , YouTube and SoundCloud.`

### 💫 Music Player \(With logging Feature\)

💨 This section is for those people who want to go more into enjoying the music without the effort to write the prefix again and again. Simply set up once and sit back and enjoy your favorite tracks. 

{% hint style="warning" %}
_**Note:-** The channel which has the logging feature will play or try to play everything entered in that channel \(**excluding commands**\)_
{% endhint %}

{% tabs %}
{% tab title="Setup 24/7 Music Player" %}
```text
dc!music setup
```

The setup process is quite simple.  
Just type the **above command** and hit Enter.  
Join a **Voice Channel** where you want the Jericho to be **`24/7 Active`**. After Joining the Voice Channel , Write `Done` and It will be Saved . After that , For Setting up **Logger Channel** \( **`Music Player U.I.`** \) , Mention a Text Channel like - **`<#Channel-Name>`** where you want to set up the logging feature.

![Glimpse of Music-Player U.I.](../.gitbook/assets/1.png)
{% endtab %}

{% tab title="Edit 24/7 Music Player" %}
```text
dc!music edit <Voice/Channel>
```

**Here,  
Voice - `Voice Channel`  
Channel - `Music Logger Channel (Music Player U.I.)`**

**After that Jericho will ask for `New Voice/Music-logger-Channel` for the Server.**
{% endtab %}

{% tab title="Delete 24/7 Music Player" %}
```text
dc!music delete <Voice/Channel/all>
```

**Here,  
Voice - `Voice Channel`  
Channel - `Music Logger Channel (Music Player U.I.)`   
all - `Delete All Configs for the Server`**

**After that Jericho will Delete for `New Voice/Music-logger-Channel` for the Server.**
{% endtab %}
{% endtabs %}

