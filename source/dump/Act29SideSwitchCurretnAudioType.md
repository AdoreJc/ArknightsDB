# Act29SideSwitchCurretnAudioType

**Namespace:** ` `


## Fields

- `String _evnSysKey`

- `Boolean _switchToOposite`

- `String _typeKey`

- `Boolean _isFirstTime`

- `Boolean _isTriggeredByBoss`

- `Boolean _muteAudio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act29SideSwitchCurretnAudioType : ActionNode
{
	private String _evnSysKey; // 0x10
	private Boolean _switchToOposite; // 0x18
	private String _typeKey; // 0x20
	private Boolean _isFirstTime; // 0x28
	private Boolean _isTriggeredByBoss; // 0x29
	private Boolean _muteAudio; // 0x2a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd2b98 VA: 0x75945eab98
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd2c00 VA: 0x75945eac00
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd2ed0 VA: 0x75945eaed0
	public Void .ctor() { }
}
```