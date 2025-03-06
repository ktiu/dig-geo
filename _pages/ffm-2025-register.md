---
title: Registration
permalink: ffm-2025-register
---

<h2 style="text-align: center">
  AK Digitale Geographien annual meeting<br>
  Goethe University Frankfurt, Campus Westend<br>
  November 6–7, 2025
</h2>

Please note:

- Registration is open until the meeting.
- There is no fee for participating or presenting.
- If you want to present at the meeting, please see the information at the end of our [call for papers](/2025-03-06-cfp-frankfurt).
- You will not be able to edit submitted information. Please e-mail us at <ffm-2025@digitale-geographien.de> for urgent changes.

<style>
  .item {
    margin-bottom: 3rem;
  }
  .item input[type=text],
  .item input[type=email]
  {
    width: 100%;
    margin-bottom: 0.2rem;
  }
  .bool {
    display: flex;
    align-items: start;
    gap: 3rem;
    margin-bottom: 0.2rem;
  }
  .check {
    display: flex;
    align-items: start;
    gap: 1rem;
    margin-bottom: 0.2rem;
  }
  .help {
    font-size: 0.8em;
  }
  .nobold {
    font-weight: normal;
  }
</style>

<form method="post" action="https://register.digitale-geographien.de/" style="margin-top: 6rem">

  <div class="item">
    <label for="email">Full name</label>
    <input type="text" name="name" minlength="5" maxlength="128" required />
    <div class="help">
      Please enter your full name as you would like it to appear on your name badge and in the program if you are presenting.
    </div>
  </div>

  <div class="item">
    <label for="email">E-mail address</label>
    <br />
    <input type="email" name="email" required />
    <div class="help">
      We will use this address to keep you up to date. Please double-check the spelling. <em><strong>Please note that you will not receive an automatic confirmation e-mail after registering.</strong></em>
    </div>
  </div>

  <div class="item">
    <label for="email">Affiliation</label>
    <br />
    <input type="text" name="affiliation" placeholder="e.g. Goethe University Frankfurt" maxlength="128" required />
    <div class="help">
      Please provide one organization that you are affiliated with. Alternatively, you can enter the name of the city where you are based. This will appear on your name badge and in the program if you are presenting.
    </div>
  </div>

  <div class="item">
    <label for="email">Are you comfortable following presentations and discussions in German?</label>
    <br />
    <div class="bool">
      <label class="nobold"><input type="radio" name="german" value="yes" required /> Yes</label>
      <label class="nobold"><input type="radio" name="german" value="no" /> No</label>
    </div>
    <div class="help">
      This will help us plan around language barriers when putting together the program.
    </div>
  </div>

  <div class="item">
    <label for="email">Are you interested in using our childcare services?<br />(Please let us know until August 31, 2025)</label>
    <br />
    <div class="bool">
      <div><label class="nobold"><input type="radio" name="childcare" value="yes" required /> Yes</label></div>
      <div><label class="nobold"><input type="radio" name="childcare" value="no" /> No</label></div>
    </div>
    <div class="help">
      During the annual meeting (excluding evening activities), we are planning to organize childcare free of charge. If you answer "yes", we will get in touch with you for more details.
    </div>
  </div>

  <div class="item">
    <label for="email">Accessibility requirements (optional)</label>
    <br />
    <input type="text" name="accessibility" placeholder="e.g. handicapped parking" maxlength="1024" />
    <div class="help">
      Please share any concerns you may personally have about accessibility of the meeting's venues and content. Feel free to include suggestions on how to mitigate any barriers.
    </div>
  </div>

  <div class="item">
    <label for="email">Dietary restrictions (optional)</label>
    <br />
    <input type="text" name="email" placeholder="e.g. vegan, halal, peanut allergy, ..." maxlength="1024" />
    <div class="help">
      This will help us make better choices for restaurants and catering.
    </div>
  </div>

  <div class="item">
    <label for="pronouns">Pronouns (optional)</label>
    <br />
    <input type="text" name="pronouns" placeholder="e.g. she / her" maxlength="128" />
    <div class="help">
      If you provide your pronouns here, we will print them on your name badge.
    </div>
  </div>

  <div class="item">
    <label for="privacy">Data privacy notice</label>
    <br />
    <div class="check">
    <div><input type="checkbox" name="privacy_consent" value="true" required /></div>
    <div>I have read and understood the following information, and I consent to my data being used as described below:</div>
    </div>
    <div class="help">
      When you submit this form, the information you provided will be securely transmitted to and stored on a server run by Goethe University (not on the server that hosts this website). We will download and use this information only for organizing the annual meeting. We will not share your information with third parties.
    </div>
  </div>

  <div style="text-align: left">
    <input type="submit" value="Submit registration"/>
  </div>

</form>
