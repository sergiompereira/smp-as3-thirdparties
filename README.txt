
LIBRARY
-------
GTween_V2_01.swc

@USE
import com.gskinner.motion.GTween;
import com.gskinner.motion.easing.*;

var _tweener:GTween;

_tweener = new GTween(_target);
_tweener.setValue("y", _endYvalue);
_tweener.duration = 0.5;
_tweener.ease = Sine.easeOut;

or

_tweener = new GTween(_target, 0.5, {alpha:1, y:100}, {ease:Sine.easeOut});



