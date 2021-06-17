# Using vue slots and modals.

## Main Focus:
<p> This fireside primarily focuses on using modals in an efficient manner. The fireside will guide the students through the common mistakes and best practices for modal usage. </p>

<ul>
<li> To start show a modal with a v-for on it. This will work but you'll have to pass props to keep the Id's unique. After showing it working make sure to stress that this is the less efficient way to do this process, we're creating tons of modals rather then reusing one.
<br>
<li> Next show off a modal using the AppState, when you click on a post it sets that as the active post and renders the modal based off that data. This create one modal that is reused for all our posts! 
<br>
<li> Finally show off slots for modals, with this method we could reuse a single modal for our entire application.
<br>
<li> Show off putting the modals in the app.vue so we can access them from anywhere
</ul>