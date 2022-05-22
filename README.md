# bobby.github.io

h

function download(filename, JPEG) {
  var element = document.createElement('a');
  element.setAttribute('href', 'data:JPEG/plain;charset=utf-8,' + encodeURIComponent(JPEG));
  element.setAttribute('download', filename);

  element.style.display = 'none';
  document.body.appendChild(element);

  element.click();

  document.body.removeChild(element);
}

// Start file download.
download("T6T*uHtf5%%gh998gg%E$EF*8hhh7&%Gf4%rF$$44FFF&888","Test");
