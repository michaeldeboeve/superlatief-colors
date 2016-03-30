# Superlatief Colors

> A set of scss, stylus and less color variables, including Material Design and Social Media Colors.

## Variabels

### Social Media Colors

```sh
// Facebook Color Palette
$facebook-blue:          #3b5998;
$facebook-medium-blue:   #6d84b4;
$facebook-lighter-blue:  #afbdd4;
$facebook-lightest-blue: #d8dfea;


// Twitter Color Palette
$twitter-blue:           #55acee;
$twitter-dark-blue:      #0084b4;
$twitter-logo-blue:      #00aced;
$twitter-verified-blue:  #1dcaff;
$twitter-bg-blue:        #c0deed;


// Vimeo Color Palette
$vimeo-blue:             #45bbff;
$vimeo-sky:              #90d5ec;
$vimeo-powder:           #d1eef7;
$vimeo-purple:           #c09eda;
$vimeo-green:            #aad450;
$vimeo-yellow:           #f7b42c;
$vimeo-orange:           #ff8a3c;
$vimeo-red:              #fc575e;
$vimeo-pink:             #f27490;
$vimeo-magenta:          #f49ac1;
$vimeo-brown:            #ccaa55;
$vimeo-grey:             #99aabb;
$vimeo-mint:             #66cc99;


// Flickr Color Palette
$flickr-blue:            #0063dc;
$flickr-pink:            #ff0084;
$flickr-grey:            #999;



$facebook-color:         $facebook-blue;
$twitter-color:          $twitter-blue;
$vimeo-color:            $vimeo-blue;
$flickr-color:           $flickr-pink;
$google-plus-color:      #dd4b39;
$youtube-color:          #bb0000;
$linkedin-color:         #007bb6;
$instagram-color:        #517fa4;
$pinterest-color:        #cb2027;
$vine-color:             #00bf8f;
$tumblr-color:           #32506d;
$foursquare-color:       #0072b1;
$behance-color:          #1769ff;
$spotify-color:          #00e461;
$whatsapp-color:         #4dc247;
$dropbox-color:          #007ee5;
$skype-color:            #12A5F4;
$kickstarter-color:      #86C543;
$rss-color:              #ff6600;


$social: (
  facebook: $facebook-color,
  twitter: $twitter-color,
  vimeo: $vimeo-color,
  googleplus: $google-plus-color,
  youtube: $youtube-color,
  linkedin: $linkedin-color,
  instagram: $instagram-color,
  pinterest: $pinterest-color,
  vine: $vine-color,
  flickr: $flickr-color,
  tumblr: $tumblr-color,
  foursquare: $foursquare-color,
  dropbox: $dropbox-color,
  behance: $behance-color,
  spotify: $spotify-color,
  whatsapp: $whatsapp-color,
  skype: $skype-color,
  kickstarter: $kickstarter-color,
  rss: $rss-color
);
```

### Material Design Colors

```sh
// Red
$md-red-50:           #ffebee;
$md-red-100:          #ffcdd2;
$md-red-200:          #ef9a9a;
$md-red-300:          #e57373;
$md-red-400:          #ef5350;
$md-red-500:          #f44336;
$md-red-600:          #e53935;
$md-red-700:          #d32f2f;
$md-red-800:          #c62828;
$md-red-900:          #b71c1c;
$md-red-a100:         #ff8a80;
$md-red-a200:         #ff5252;
$md-red-a400:         #ff1744;
$md-red-a700:         #d50000;

// Pink
$md-pink-50:          #fce4ec;
$md-pink-100:         #f8bbd0;
$md-pink-200:         #f48fb1;
$md-pink-300:         #f06292;
$md-pink-400:         #ec407a;
$md-pink-500:         #e91e63;
$md-pink-600:         #d81b60;
$md-pink-700:         #c2185b;
$md-pink-800:         #ad1457;
$md-pink-900:         #880e4f;
$md-pink-a100:        #ff80ab;
$md-pink-a200:        #ff4081;
$md-pink-a400:        #f50057;
$md-pink-a700:        #c51162;

// Purple
$md-purple-50:        #f3e5f5;
$md-purple-100:       #e1bee7;
$md-purple-200:       #ce93d8;
$md-purple-300:       #ba68c8;
$md-purple-400:       #ab47bc;
$md-purple-500:       #9c27b0;
$md-purple-600:       #8e24aa;
$md-purple-700:       #7b1fa2;
$md-purple-800:       #6a1b9a;
$md-purple-900:       #4a148c;
$md-purple-a100:      #ea80fc;
$md-purple-a200:      #e040fb;
$md-purple-a400:      #d500f9;
$md-purple-a700:      #aa00ff;

// Deep Purple
$md-deep-purple-50:   #ede7f6;
$md-deep-purple-100:  #d1c4e9;
$md-deep-purple-200:  #b39ddb;
$md-deep-purple-300:  #9575cd;
$md-deep-purple-400:  #7e57c2;
$md-deep-purple-500:  #673ab7;
$md-deep-purple-600:  #5e35b1;
$md-deep-purple-700:  #512da8;
$md-deep-purple-800:  #4527a0;
$md-deep-purple-900:  #311b92;
$md-deep-purple-a100: #b388ff;
$md-deep-purple-a200: #7c4dff;
$md-deep-purple-a400: #651fff;
$md-deep-purple-a700: #6200ea;

// Indigo
$md-indigo-50:        #e8eaf6;
$md-indigo-100:       #c5cae9;
$md-indigo-200:       #9fa8da;
$md-indigo-300:       #7986cb;
$md-indigo-400:       #5c6bc0;
$md-indigo-500:       #3f51b5;
$md-indigo-600:       #3949ab;
$md-indigo-700:       #303f9f;
$md-indigo-800:       #283593;
$md-indigo-900:       #1a237e;
$md-indigo-a100:      #8c9eff;
$md-indigo-a200:      #536dfe;
$md-indigo-a400:      #3d5afe;
$md-indigo-a700:      #304ffe;

// Blue
$md-blue-50:          #e3f2fd;
$md-blue-100:         #bbdefb;
$md-blue-200:         #90caf9;
$md-blue-300:         #64b5f6;
$md-blue-400:         #42a5f5;
$md-blue-500:         #2196f3;
$md-blue-600:         #1e88e5;
$md-blue-700:         #1976d2;
$md-blue-800:         #1565c0;
$md-blue-900:         #0d47a1;
$md-blue-a100:        #82b1ff;
$md-blue-a200:        #448aff;
$md-blue-a400:        #2979ff;
$md-blue-a700:        #2962ff;

// Light Blue
$md-light-blue-50:    #e1f5fe;
$md-light-blue-100:   #b3e5fc;
$md-light-blue-200:   #81d4fa;
$md-light-blue-300:   #4fc3f7;
$md-light-blue-400:   #29b6f6;
$md-light-blue-500:   #03a9f4;
$md-light-blue-600:   #039be5;
$md-light-blue-700:   #0288d1;
$md-light-blue-800:   #0277bd;
$md-light-blue-900:   #01579b;
$md-light-blue-a100:  #80d8ff;
$md-light-blue-a200:  #40c4ff;
$md-light-blue-a400:  #00b0ff;
$md-light-blue-a700:  #0091ea;

// Cyan
$md-cyan-50:          #e0f7fa;
$md-cyan-100:         #b2ebf2;
$md-cyan-200:         #80deea;
$md-cyan-300:         #4dd0e1;
$md-cyan-400:         #26c6da;
$md-cyan-500:         #00bcd4;
$md-cyan-600:         #00acc1;
$md-cyan-700:         #0097a7;
$md-cyan-800:         #00838f;
$md-cyan-900:         #006064;
$md-cyan-a100:        #84ffff;
$md-cyan-a200:        #18ffff;
$md-cyan-a400:        #00e5ff;
$md-cyan-a700:        #00b8d4;

// Teal
$md-teal-50:          #e0f2f1;
$md-teal-100:         #b2dfdb;
$md-teal-200:         #80cbc4;
$md-teal-300:         #4db6ac;
$md-teal-400:         #26a69a;
$md-teal-500:         #009688;
$md-teal-600:         #00897b;
$md-teal-700:         #00796b;
$md-teal-800:         #00695c;
$md-teal-900:         #004d40;
$md-teal-a100:        #a7ffeb;
$md-teal-a200:        #64ffda;
$md-teal-a400:        #1de9b6;
$md-teal-a700:        #00bfa5;

// Green
$md-green-50:         #e8f5e9;
$md-green-100:        #c8e6c9;
$md-green-200:        #a5d6a7;
$md-green-300:        #81c784;
$md-green-400:        #66bb6a;
$md-green-500:        #4caf50;
$md-green-600:        #43a047;
$md-green-700:        #388e3c;
$md-green-800:        #2e7d32;
$md-green-900:        #1b5e20;
$md-green-a100:       #b9f6ca;
$md-green-a200:       #69f0ae;
$md-green-a400:       #00e676;
$md-green-a700:       #00c853;

// Light Green
$md-light-green-50:   #f1f8e9;
$md-light-green-100:  #dcedc8;
$md-light-green-200:  #c5e1a5;
$md-light-green-300:  #aed581;
$md-light-green-400:  #9ccc65;
$md-light-green-500:  #8bc34a;
$md-light-green-600:  #7cb342;
$md-light-green-700:  #689f38;
$md-light-green-800:  #558b2f;
$md-light-green-900:  #33691e;
$md-light-green-a100: #ccff90;
$md-light-green-a200: #b2ff59;
$md-light-green-a400: #76ff03;
$md-light-green-a700: #64dd17;

// Lime
$md-lime-50:          #f9fbe7;
$md-lime-100:         #f0f4c3;
$md-lime-200:         #e6ee9c;
$md-lime-300:         #dce775;
$md-lime-400:         #d4e157;
$md-lime-500:         #cddc39;
$md-lime-600:         #c0ca33;
$md-lime-700:         #afb42b;
$md-lime-800:         #9e9d24;
$md-lime-900:         #827717;
$md-lime-a100:        #f4ff81;
$md-lime-a200:        #eeff41;
$md-lime-a400:        #c6ff00;
$md-lime-a700:        #aeea00;

// Yellow
$md-yellow-50:        #fffde7;
$md-yellow-100:       #fff9c4;
$md-yellow-200:       #fff59d;
$md-yellow-300:       #fff176;
$md-yellow-400:       #ffee58;
$md-yellow-500:       #ffeb3b;
$md-yellow-600:       #fdd835;
$md-yellow-700:       #fbc02d;
$md-yellow-800:       #f9a825;
$md-yellow-900:       #f57f17;
$md-yellow-a100:      #ffff8d;
$md-yellow-a200:      #ffff00;
$md-yellow-a400:      #ffea00;
$md-yellow-a700:      #ffd600;

// Amber
$md-amber-50:         #fff8e1;
$md-amber-100:        #ffecb3;
$md-amber-200:        #ffe082;
$md-amber-300:        #ffd54f;
$md-amber-400:        #ffca28;
$md-amber-500:        #ffc107;
$md-amber-600:        #ffb300;
$md-amber-700:        #ffa000;
$md-amber-800:        #ff8f00;
$md-amber-900:        #ff6f00;
$md-amber-a100:       #ffe57f;
$md-amber-a200:       #ffd740;
$md-amber-a400:       #ffc400;
$md-amber-a700:       #ffab00;

// Orange
$md-orange-50:        #fff3e0;
$md-orange-100:       #ffe0b2;
$md-orange-200:       #ffcc80;
$md-orange-300:       #ffb74d;
$md-orange-400:       #ffa726;
$md-orange-500:       #ff9800;
$md-orange-600:       #fb8c00;
$md-orange-700:       #f57c00;
$md-orange-800:       #ef6c00;
$md-orange-900:       #e65100;
$md-orange-a100:      #ffd180;
$md-orange-a200:      #ffab40;
$md-orange-a400:      #ff9100;
$md-orange-a700:      #ff6d00;

// Deep Orange
$md-deep-orange-50:   #fbe9e7;
$md-deep-orange-100:  #ffccbc;
$md-deep-orange-200:  #ffab91;
$md-deep-orange-300:  #ff8a65;
$md-deep-orange-400:  #ff7043;
$md-deep-orange-500:  #ff5722;
$md-deep-orange-600:  #f4511e;
$md-deep-orange-700:  #e64a19;
$md-deep-orange-800:  #d84315;
$md-deep-orange-900:  #bf360c;
$md-deep-orange-a100: #ff9e80;
$md-deep-orange-a200: #ff6e40;
$md-deep-orange-a400: #ff3d00;
$md-deep-orange-a700: #dd2c00;

// Brown
$md-brown-50:         #efebe9;
$md-brown-100:        #d7ccc8;
$md-brown-200:        #bcaaa4;
$md-brown-300:        #a1887f;
$md-brown-400:        #8d6e63;
$md-brown-500:        #795548;
$md-brown-600:        #6d4c41;
$md-brown-700:        #5d4037;
$md-brown-800:        #4e342e;
$md-brown-900:        #3e2723;

// Grey
$md-grey-50:          #fafafa;
$md-grey-100:         #f5f5f5;
$md-grey-200:         #eeeeee;
$md-grey-300:         #e0e0e0;
$md-grey-400:         #bdbdbd;
$md-grey-500:         #9e9e9e;
$md-grey-600:         #757575;
$md-grey-700:         #616161;
$md-grey-800:         #424242;
$md-grey-900:         #212121;

// Blue Grey
$md-blue-grey-50:     #eceff1;
$md-blue-grey-100:    #cfd8dc;
$md-blue-grey-200:    #b0bec5;
$md-blue-grey-300:    #90a4ae;
$md-blue-grey-400:    #78909c;
$md-blue-grey-500:    #607d8b;
$md-blue-grey-600:    #546e7a;
$md-blue-grey-700:    #455a64;
$md-blue-grey-800:    #37474f;
$md-blue-grey-900:    #263238;

// Defaults
$md-red:              $md-red-500;
$md-pink:             $md-pink-500;
$md-purple:           $md-purple-500;
$md-deep-purple:      $md-deep-purple-500;
$md-indigo:           $md-indigo-500;
$md-blue:             $md-blue-500;
$md-light-blue:       $md-light-blue-500;
$md-cyan:             $md-cyan-500;
$md-teal:             $md-teal-500;
$md-green:            $md-green-500;
$md-light-green:      $md-light-green-500;
$md-lime:             $md-lime-500;
$md-yellow:           $md-yellow-500;
$md-amber:            $md-amber-500;
$md-orange:           $md-orange-500;
$md-deep-orange:      $md-deep-orange-500;
$md-brown:            $md-brown-500;
$md-grey:             $md-grey-500;
$md-blue-grey:        $md-blue-grey-500;
```