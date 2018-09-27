# week4-Javascripting

var getli=document.getElementById('sidebar').getElementsByTagName('ul')[0].getElementsByTagName('li');
    getli[1].innerHTML="<a href='#section1'>Greetings List Item! I'm a string from another planet!</a>";

document.getElementById('section1').innerHTML="Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

        var parent=getElementById('section2');
        var child=getElementById('empty-me');
        parent.removeChild(child);

        var elem = document.getElementById("section3");
        elem.parentNode.removeChild(elem);

        document.getElementsByTagName("h2").addEventListener("click", function(){
          alert("Hey Hey Hey!");
          });
