import './style.css'

document.getElementById('theme').onclick = function () {
  var root = document.documentElement;
  var next = root.getAttribute('data-theme') === 'dark' ? 'light' : 'dark';
  root.setAttribute('data-theme', next);
  try { localStorage.setItem('theme', next); } catch (e) {}
};
document.getElementById('go').onclick = function () {
  var ok = /^\S+@\S+\.\S+$/.test(document.getElementById('email').value.trim());
  document.getElementById('msg').textContent = ok
    ? 'Thanks, you’re on the list. (Demo form: connect Formspree to collect real emails.)'
    : 'Enter a valid email address, like you@email.com.';
};