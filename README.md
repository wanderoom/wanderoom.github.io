# wanderoom.github.io
function init() {
  Tabletop.init( { key: 'https://docs.google.com/spreadsheets/d/19Q_c1hcGIkLORluUacrXDFGjH4bKv3clPHhX0HqXhrI/pubhtml',
                   callback: function(data, tabletop) { 
                       console.log(data)
                   },
                   simpleSheet: true } )
}
window.addEventListener('DOMContentLoaded', init)
