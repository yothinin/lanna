# lanna
Lanna unicode layout for Ubuntu.
ᩃᩴᩣᨯᩢ᩠ᨷᨲᩴ᩠᩵ᩋᨻᩲᨶᩦ᩶ᨧᩢᨧᩣᨳᩮᩥ᩠ᨦᩅᩥᨵᩦᨠᩣ᩠ᨶᨸᩯ᩠ᨦᨼᩲᩖ᩺ unicode keyboard ᨻᩮᩥ᩠᩵ᩋᨧᩢᨲᩮ᩠ᨠᩡᨻᩥᨾᩛ᩺ᨲᩫ᩠ᩅᨾᩮᩥ᩠ᩋᨦᨶᩲᩁᨷᩫ᩠ᨷᩒᩋᩮ᩠ᩈ Ubuntu

᪁ ᨧᩢᨲᩢ᩠ᩋᨦᩈᩕ᩶ᩣ᩠ᨦᨸᩯ᩠ᨦᨼᩲᩖ᩺ ln ᨻᩮᩥ᩠᩵ᩋᨠᩮ᩠ᨷᩡᩁᩉᩢ᩠ᩈᨸᩩ᩵ᨾᨲᩮ᩠ᨠᩡᩈᩮ᩠ᨿᨠ᩠᩵ᩋᩁ ᨯᩰ᩠ᨿᨣ᩠᩶ᩋᨷᨻᩦᩢᨼᩲᩖ᩺ ln ᨻᩲᩅᩲ᩶ᨶᩲ /usr/share/X11/xkb/symbols/

᪂ ᨠᩯ᩶ᨡᩲᨼᩲᩖ᩺ /usr/share/X11/xkb/rules/evdev.xml ᨲᩮᩥ᩠᩵ᩋᨾᨡᩴ᩠᩶ᩋᨾᩪᩃᨯᩢ᩠ᨦᨶᩦᩢ
   <layoutList>
     <layout>
      <configItem>
        <name>ln</name>
        <!-- Keyboard indicator for Lanna layouts -->
        <shortDescription>ln</shortDescription>
        <description>Lanna</description>
        <languageList>
          <iso639Id>ln</iso639Id>
        </languageList>
      </configItem>
    </layout>
    ...
  </layoutList>

᪃ ᩁ᩠ᨿᨷᩁ᩠᩶ᩋ᩠ᨿᩓ᩠ᩅᩉᩨ᩶ᩁᩦᨷᩪᨴᨣᩕᩮᩥ᩠᩵ᩋᨦᨠ᩠᩵ᩋᩁ

᪄ ᨻᩥᨾᩛ᩺ᨯᩢ᩠ᨦᨶᩦ᩶
    gsettings set org.gnome.desktop.input-sources sources "[('xkb', 'us'), ('xkb', 'th'), ('xkb', 'ln')]"
    ᨻᩮᩥ᩠᩵ᩋᨧᩢᨻᩮᩥ᩠᩵ᨾᨸᩩ᩵ᨾᨽᩣᩈᩣ ᨸᨠ᩠ᨲᩥᨧᩢᨻᩮᩥ᩠᩵ᨾᨶᩲ settings/Language/input source ᨲᩯ᩵ᩈᩢ᩠᩵ᨦᨶᩲᨤ᩠ᨾᨾᩣ᩠ᨶᩃᩲ᩠ᨶ᩺ᨣᩴ᩵ᨦ᩵ᩣ᩠ᨿᨯᩦ
    
ᨸᩩ᩵ᨾ Level 3 ᨧᩢᨸᩮ᩠ᨶᨸᩩ᩵ᨾ Right+Alt ᨳ᩶ᩣᨠᩴᩣᩉ᩠ᨶᩫᨯᩓ᩠ᩅᨩᩲ᩶ᨷᩴ᩵ᨯᩲ᩶ᩉᩨ᩶ᩃᩫ᩠ᨦ tweaks ᩓ᩠ᩅᨻᩲᨠᩴᩣᩉᩫ᩠ᨶᨯᨴᩦ᩵ Keyboard&Mouse/Additional Layout Options/Key to choose the 3rd level//Right Alt
