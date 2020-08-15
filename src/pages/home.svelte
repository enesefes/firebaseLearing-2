<Page name="home">
  <!-- Top Navbar -->
  <Navbar >
    
    <NavTitle >TurkToWorld</NavTitle>
    <NavRight>
      <Link iconIos="f7:menu" iconAurora="f7:menu" iconMd="material:menu" panelOpen="right" />
    </NavRight>
    
  </Navbar>
  <!-- Toolbar -->
  
  <!-- SIGN UP MODAL -->
  <div id="modal-signup" class="modal">
    <div class="modal-content">
      <h4>Sign up</h4><br />
      <form id="signup-form">
        <div class="input-field">
          <input type="email" id="signup-email" required />
          <label for="signup-email">Email address</label>
        </div>
        <div class="input-field">
          <input type="password" id="signup-password" required />
          <label for="signup-password">Choose password</label>
        </div>
        <div class="input-field">
          <input type="text" id="signup-name" required />
          <label for="signup-name">Name</label>
        </div>
        <div class="input-field">
          <input type="text" id="signup-bio" required />
          <label for="signup-bio">One Line Bio</label>
        </div>
        
        <button class="btn yellow darken-2 z-depth-0">Sign up</button>
      </form>
    </div>
  </div>

  <!-- LOGIN MODAL -->
  <div id="modal-login" class="modal">
    <div class="modal-content">
      <h4>Login</h4><br />
      <form id="login-form">
        <div class="input-field">
          <input type="email" id="login-email" required />
          <label for="login-email">Email address</label>
        </div>
        <div class="input-field">
          <input type="password" id="login-password" required />
          <label for="login-password">Your password</label>
        </div>
        <button class="btn yellow darken-2 z-depth-0">Login</button>
      </form>
    </div>
  </div>
  <!-- ACCOUNT MODAL -->
  <div id="modal-account" class="modal">
    <div class="modal-content center-align">
      <h4>Account details</h4><br />
      <div class="account-details"></div>
    </div>
  </div>

  <!-- CREATE GUIDE MODAL -->
  <div id="modal-create" class="modal">
    <div class="modal-content">
      <h4>Create Guide</h4><br />
      <form id="create-form">
        <div class="input-field">
          <input type="text" id="title" required>
          <label for="title">Guide Title</label>
        </div>
        <div class="input-field">
          <textarea id="content" class="materialize-textarea" required></textarea>
          <label for="content">Guide Content</label>
        </div>
        <button class="btn yellow darken-2 z-depth-0">Create</button>
      </form>
    </div>
  </div>
  <!-- GUIDE LIST -->
  <div class="container" style="margin-top: 40px;">
    <ul class="collapsible z-depth-0 guides" style="border: none;">
      
    </ul>
  </div>
  
</Page>
<script>
  import {
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button
  } from 'framework7-svelte';
</script>