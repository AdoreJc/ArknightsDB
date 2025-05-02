# RewardTrackPoint

**Namespace:** ` `


## Fields

- `Boolean m_haveAvailFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewardTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_haveAvailFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x295002c VA: 0x7594f6802c
	public Boolean get_isShow() { }
	// RVA: 0x2950094 VA: 0x7594f68094
	public Void UpdateState(Object param) { }
	// RVA: 0x2950180 VA: 0x7594f68180
	public Void .ctor() { }
}
```