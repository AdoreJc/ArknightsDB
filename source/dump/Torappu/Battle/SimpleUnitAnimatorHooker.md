# SimpleUnitAnimatorHooker

**Namespace:** `Torappu.Battle`


## Methods

- `Void ChangeReplaceAnimPairs(ReplacePair[], Boolean)`

- `Void ChangeExcludeAnimKeys(String[], Boolean)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SimpleUnitAnimatorHooker : UnitAnimatorHooker
{
	private String[] _excludeAnimKeys; // 0x18
	private ReplacePair[] _replaceAnimPairs; // 0x20
	private DisableAnimSwitchSetting[] _disableSwitchSettings; // 0x28
	private List`1 m_replaceAnimPairs; // 0x30
	private List`1 m_excludeAnimKeys; // 0x38


	// RVA: 0x3f34864 VA: 0x759654c864
	public override Boolean TryHookAnimation(String animKey, out String newAnimKey) { }
	// RVA: 0x3f34970 VA: 0x759654c970
	public override Boolean ValidateAnimSwitchable(String sourceAnimName, String targetAnimName) { }
	// RVA: 0x3f34a7c VA: 0x759654ca7c
	public Void ChangeReplaceAnimPairs(ReplacePair[] changeAnimPairs, Boolean isOverwrite) { }
	// RVA: 0x3f34cb0 VA: 0x759654ccb0
	public Void ChangeExcludeAnimKeys(String[] changeAnimKeys, Boolean isOverwrite) { }
	// RVA: 0x3f34e70 VA: 0x759654ce70
	private Void Awake() { }
	// RVA: 0x3f34f5c VA: 0x759654cf5c
	public Void .ctor() { }
}
```