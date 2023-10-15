window.addEventListener("scroll", function() {
  var header = document.querySelector("header.sticky");
  if (window.scrollY > 0) {
    header.classList.add("sticky-scroll");
  } else {
    header.classList.remove("sticky-scroll");
  }
});# Borg
