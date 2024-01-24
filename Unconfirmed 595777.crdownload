



let SignOut= document.getElementById("show-logout");

let Signout = ()=>{
  sessionStorage.removeItem("user-creds");
  sessionStorage.removeItem("user-info");
  window.location.href='login.html'
  alert("Do you really want to log out?")

 
}



SignOut.addEventListener('click' ,Signout)





const arrows = document.querySelectorAll(".arrow");
const movieLists = document.querySelectorAll(".movie-list");

arrows.forEach((arrow, i) => {
  const itemNumber = movieLists[i].querySelectorAll("img").length;
  let clickCounter = 0;
  arrow.addEventListener("click", () => {
    const ratio = Math.floor(window.innerWidth / 200);
    clickCounter++;
    if (itemNumber - (2 + clickCounter) + (2 - ratio) >= 0) {
      movieLists[i].style.transform = `translateX(${movieLists[i].computedStyleMap().get("transform")[0].x.value - 600
        }px)`;
    } else {
      movieLists[i].style.transform = "translateX(0)";
      clickCounter = 0;
    }
  });

  console.log(Math.floor(window.innerWidth / 200));
});




// $(document).ready(function () {
//   $('.rating-stars i').click(function () {
//       $(this).siblings().removeClass('selected');

//       $(this).addClass('selected').prevAll().addClass('selected');

//   });

  
// });



// document.addEventListener("DOMContentLoaded", function () {

//   const watchlistIcons = document.querySelectorAll('.watchlist-icon');


//   watchlistIcons.forEach(icon => {
//     icon.addEventListener('click', (e) => {
//       const movieTitle = e.target.getAttribute('data-movie');
//       toggleWatchlist(icon);
//       alert(`Toggled "${movieTitle}" in your watchlist!`);
//     });
//   });
// });


function toggleWatchlist(icon) {
  icon.classList.toggle('active');
}





    document.addEventListener("DOMContentLoaded", function () {
        var openModalButton = document.getElementById("open-modal");
        var dropdownContent = document.getElementById("profile-dropdown-content");

        // Toggle the display of the dropdown content when clicking on profile info
        openModalButton.addEventListener("click", function () {
            dropdownContent.style.display = (dropdownContent.style.display === "block") ? "none" : "block";
        });

        // Close the dropdown content when clicking outside the dropdown
        window.addEventListener("click", function (event) {
            if (!event.target.matches('.profile-dropdown') && !event.target.matches('.profile-info')) {
                dropdownContent.style.display = "none";
            }
        });
    });























