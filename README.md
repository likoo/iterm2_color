iterm2_color
============

function tab_color() {
  echo -n -e "\033]6;1;bg;red;brightness;$1\a"
  echo -n -e "\033]6;1;bg;green;brightness;$2\a"
  echo -n -e "\033]6;1;bg;blue;brightness;$3\a"
}
 
tab_color 219 154  88 #orange
tab_color 92 155 204 # blue
tab_color 195  89  76 #red
tab_color 240 240   0 #yellow
