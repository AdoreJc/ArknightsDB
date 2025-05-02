# Act29SideCheckCurrentAudioType

**Namespace:** ` `


## Fields

- `String _evnSysKey`

- `AudioType _audioType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act29SideCheckCurrentAudioType : ActionNode
{
	private String _evnSysKey; // 0x10
	private AudioType _audioType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd28f8 VA: 0x75945ea8f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd2960 VA: 0x75945ea960
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd2af8 VA: 0x75945eaaf8
	public Void .ctor() { }
}
```