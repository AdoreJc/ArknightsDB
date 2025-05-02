# CharRepoCardTrackPointViewModel

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `Boolean m_hasTrackPoint`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharRepoCardTrackPointViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_hasTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x2cfc428 VA: 0x7595314428
	public Boolean get_isShow() { }
	// RVA: 0x2cfc490 VA: 0x7595314490
	public Void UpdateState(Object param) { }
	// RVA: 0x2cfc574 VA: 0x7595314574
	public Void .ctor() { }
}
```