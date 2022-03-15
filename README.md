# Followers-from-Google
Goolge Plus
$.ajax({

  type: 'GET',

  dataType: 'json',

  url: 'https://www.googleapis.com/plus/v1/people/Google+_ID?key=API_Key',

  success: function(data) {

    var gpluscount = data.circledByCount;

    $('.gplus-count').html(gpluscount);

  }

});
