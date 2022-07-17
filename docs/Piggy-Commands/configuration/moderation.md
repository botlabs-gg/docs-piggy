# Moderation
These are the commands related to the Moderation feature of Piggy.

## kick
Kicking a member from a server will remove them while they still can join back the server any time they wish to.
<dl>
<dt><code><b>/kick <i>[user] [reason]</i></b></code>
<dd>Kick users.
<ul style="list-style-type: none;">
<li><code>user</code><font style="color:#FF0000">*</font><br>
User to kick.
</ul>
<ul style="list-style-type: none;">
<li><code>reason</code><br>
Why are they being kicked.
</ul>
</dl>

## ban
Banning a member from a server will remove them and they won't be able to join back until they are unbanned.
<dl>
<dt><code><b>/ban <i>[user-id] [username]</i></b></code>
<dd>Ban server members.
<ul style="list-style-type: none;">
<li><code>user-id</code><br>
Enter the User ID of the member you want to ban.
</ul>
<ul style="list-style-type: none;">
<li><code>username</code><br>
Enter the username of the member you want to ban.
</ul>
</dl>

## unban
Unbanning a member from a server will allow them to rejoin the server whenever they want to.
<dl>
<dt><code><b>/unban <i>[user-id] [username]</i></b></code>
<dd>Unban server members.
<ul style="list-style-type: none;">
<li><code>user-id</code><br>
Enter the User ID of the member you want to unban.
</ul>
<ul style="list-style-type: none;">
<li><code>username</code><br>
Enter the username of the member you want to unban.
</ul>
</dl>

## mute
Muting a server member would make them unable to send messages but they would still be a part of the server and would be able to view all messages. If you do not already have a Mute role then this command can create one for you.
<dl>
<dt><code><b>/mute <i>[user-id] [username] [create-role]</i></b></code>
<dd>Mute server members.
<ul style="list-style-type: none;">
<li><code>user-id</code><br>
Enter the User ID of the member you want to mute.
</ul>
<ul style="list-style-type: none;">
<li><code>username</code><br>
Enter the username of the member you want to mute.
</ul>
<ul style="list-style-type: none;">
<li><code>create-role</code><br>
Create mute role to be assigned to users who are being muted.
</ul>
</dl>

## unmute
Unmuting a server member would allow them to be able to send messages like regular users again.
<dl>
<dt><code><b>/unmute <i>[user-id] [username]</i></b></code>
<dd>Mute server members.
<ul style="list-style-type: none;">
<li><code>user-id</code><br>
Enter the User ID of the member you want to unmute.
</ul>
<ul style="list-style-type: none;">
<li><code>username</code><br>
Enter the username of the member you want to unmute.
</ul>
</dl>

## cleanup check
Old users are the users which haven't interacted with the bot or the server in a long time.
<dl>
<dt><code><b>/cleanup check</b></code>
<dd>Generate list of old users.
</dl>

## cleanup all
Cleaning up old users would remove them from the Piggy database.
<dl>
<dt><code><b>/cleanup all</b></code>
<dd>Cleanup old users.
</dl>