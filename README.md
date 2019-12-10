# Survey-Form
Survey Form for SSJKA
<div class="container">
  <header class="header">
    <h1 id="title" class="title">S.S.J.K.A</h1>
    <p id="subheader" class="subheader text-center">South Sefton Ju Jitsu & Kabudo Academy 
    </p>
<p id="description" class="description" text-left>South Seftons premier Ju Jistsu Acadamy, Would you like to</p>
<ul class="list">
<li><strong>Try Martial Arts</strong></li>
<li><strong>Build Confidence</strong></li>
<li><strong>Work Out</strong></li>
<li><strong>Make Freinds</strong></li>
</ul>
<p class="info">Then fill in the form below, answer a few questions and come along to a class. All ages welcome. 
</p> 
  </header>
  <form id="survey-form">
    <div class="form-group">
      <label id="name-label" for="name">Name</label>
      <input
        type="text"
        name="name"
        id="name"
        class="form-control"
        placeholder="Enter your name"
        required
      />
    </div>
    <div class="form-group">
      <label id="email-label" for="email">Email</label>
      <input
        type="email"
        name="email"
        id="email"
        class="form-control"
        placeholder="Enter your Email"
        required
      />
    </div>
    <div class="form-group">
      <label id="number-label" for="number"
        >Age<span class="clue">(optional)</span></label
      >
      <input
        type="number"
        name="age"
        id="number"
        min="5"
        max="99"
        class="form-control"
        placeholder="Age"
      />
    </div>
        <div class="form-group">
      <p></p>
      <select id="dropdown" name="role" class="form-control" required>
        <option disabled selected value>Select Type of Class</option>
        <option value="Ju Jitsu">Ju Jitsu</option>
        <option value="Kobudo">Kobudo</option>
        <option value="Ju Jistsu & Kobudo">Ju Jistsu & Kobudo</option>
        <option value="Sport Nunchuk">Sport Nunchuk</option>
        <option value="Keep Fit">Keep Fit</option>
      </select>
    </div>
       <div class="form-group">
      <p>Martial Arts Experiance</p>
      <label>
        <input
          name="user-recommend"
          value="Yes"
          type="radio"
          class="input-radio"
          checked
        />Yes</label
      >
      <label>
        <input
          name="user-recommend"
          value="No"
          type="radio"
          class="input-radio"
        />No</label
      >
</div>
                <div class="form-group">
      <p>Type of Martial Arts</p>
      <select id="dropdown" name="role" class="form-control" required>
        <option disabled selected value>Select Martial Art</option>
        <option value="Karate">Karate</option>
        <option value="Kick Boxing">Kick Boxing</option>
        <option value="Judo">Judo</option>
        <option value="Krav Magra">Krav Magra</option>
        <option value="Ninjitsu">Ninjitsu</option>
	<option value="other">Other</option>
      </select>
      <div class="form-group">
      <label id="name-label" for="name">If Other</label>
      <input
        type="text"
        name="If other"
        id="if other"
        class="form-control"
        placeholder="If Other"
        required
     </div> 
<div class="form-group">
      <label id="name-label" for="name">Belt or Grade Obtained</label>
      <input
        type="text"
        name="Belt or Grade"
        id="Belt or Grade"
        class="form-control"
        placeholder="Belt or Grade"
        required
     </div>             
    </div>
       <div class="form-group">
    </div>
<div class="form-group">
      <p>Day of Class
      </p>
      <select id="Day of Class" name="Day of Class" class="form-control" required>
        <option disabled selected value>Day</option>
        <option value=>Monday</option>
        <option value=>Tuesday</option>
        <option value=>Wednesday</option>
        <option value=>Thursday</option>
        <option value=>Friday</option>
        <option value=>Saturday</option>
      </select>
    </div>
     <div class="form-group">
      <p>Type of Class</p>
      <label>
        <input
          name="user-recommend"
          value="Public"
          type="radio"
          class="input-radio"
          checked
        />Public</label
      >
      <label>
        <input
          name="user-recommend"
          value="Private"
          type="radio"
          class="input-radio"
        />Private</label>    
      </div>
       <div class="form-group">
      <p>Any speciality you would like to  take part in?
        <span class="clue">(Check all that apply)</span>
      </p>

      <label>Sword<input
          name="prefer"
          value="Sword"
          type="checkbox"
          class="input-checkbox"
        /></label
      >
      <label>Nunchuck
        <input
          name="prefer"
          value="Nunchuck"
          type="checkbox"
          class="input-checkbox"
        /></label
      >
      <label>Bo/Jo<input
          name="prefer"
          value="Bo/Jo"
          type="checkbox"
          class="input-checkbox"
        /></label>
      <label>Sai<input
          name="prefer"
          value="Sai"
          type="checkbox"
          class="input-checkbox"
        /></label>
       <label>Tonfa<input
          name="prefer"
          value="Tonfa"
          type="checkbox"
          class="input-checkbox"
        /></label>
  
 </div>
     <div class="form-group">
      <p>Any questions? feel free to ask</p>
      <textarea
        id="comments"
        class="input-textarea"
        name="questions"
        placeholder="Enter your questions here..."
      ></textarea>
    </div>

    <div class="form-group">
      <button type="submit" id="submit" class="submit-button">
        Submit
      </button>
    </div>
  </form>
</div>
