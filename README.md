<h2>  Hi, I'm Agustina ! <img src="https://media.giphy.com/media/gitdNOfXczQxBZjqd4/giphy.gif" width="150"> 
<img align='right' src="https://media.giphy.com/media/26Fxy3Iz1ari8oytO/giphy.gif" width="200"></h2>
<p><em>Frontend Development Student at <a href="https://www.utn.edu.ar/es/">U.T.N. </a></br>
</em></p>

[![Linkedin: agustinaprats](https://img.shields.io/badge/-agustinaprats-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/agustinaprats/)](https://www.linkedin.com/in/agustina-prats-1157a916/)



###  <img src="https://media.giphy.com/media/igJPynWJ6ZfUChLAD6/giphy.gif" width="100"> A little more about me...  

```javascript
const agusprats = require('agusprats');
const mongoose = require('mongoose');
const Schema = mongoose.Schema;

const skillSchema = newSchema({
     Javascript: {required: true},
     Matr: {required: true},
     HTML5: {required: true},
     CSS3: {required: true},
     tools: {
          type: Schema.Types.ObjectId,
          ref:'tool',
     }
});

const toolSchema = new Schema({
     React: String,
     NodeJs: String,
     Mongodb: String,
     Angular: String,
     Bootstrap: String,
     seller: {
            type: Schema.Types.ObjectId,
            ref: 'skill',
     }
});       

module.exports = mongoose.model('skill', skillSchema);
module.exports = mongoose.model('tool', toolSchema);

```


---
- 🔭  I’m currently working on my portfolio
- 🤔  I’m currently learning how to deploy applications
- 😄  Fun fact: I´m also a lawyer and photographer


<!--
**agusprats/agusprats** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
