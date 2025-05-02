# RO4DLC2EndBossSealTileSkill

**Namespace:** ` `


## Fields

- `String _evnSysKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RO4DLC2EndBossSealTileSkill : ActionNode
{
	private String _evnSysKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd38b4 VA: 0x75945eb8b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd391c VA: 0x75945eb91c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd3a70 VA: 0x75945eba70
	public Void .ctor() { }
}
```