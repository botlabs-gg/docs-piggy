# Adventures
These are the commands related to the Adventure feature of Piggy RPG.

## adventure
Adventures are basically missions that you can send your Piggy on for a set amount of time before your Piggy returns. Adventures might end in a success or a failure. A Piggy can only go on one consecutive adventure, you can start another adventure once the adventure in progress gets over.
<dl>
<dt><code><b>/adventure set-piggy <i>[piggy-id]</i></b></code>
<dd>Set your default adventure Piggy. You are given 1 option with this command as follows:
<ul style="list-style-type: none;">
<li><code>piggy-id</code><br>
Enter the Piggy ID of the Piggy you want to rename. The Piggy ID are the digits after the <b>#</b> in your Piggy's name. You can check this using <code>/farm</code> or on your Dashboard.
</ul>
<dt><code><b>/adventure reset-piggy</b></code>
<dd>Reset your current default adventure Piggy.
<dt><code><b>/adventure start</b></code>
<dd>Send your Piggy for an adventure.
<dt><code><b>/adventure end</b></code>
<dd>End your active adventure.
<dt><code><b>/adventure claim</b></code>
<dd>Claim your adventure rewards.
<dt><code><b>/adventure stats <i>[type]</i></b></code>
<dd>Check your global/local adventure stats. Select <b>local</b> for server stats and <b>global</b> for stats across different servers:
<ul style="list-style-type: none;">
<li><code>type</code><br>Local
<li>Global
</ul>
</dl>