# HolderHandler

**Namespace:** ` `


## Fields

- `LocalTrackStore m_store`


## Methods

- `Boolean DoTrackTrigger(TrackTrigger)`

- `Int64 GetTrackTypeVersion(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HolderHandler : IHotfixable
{
	private LocalTrackStore m_store; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_DoTrackTrigger; // 0x8
	private static DelegateBridge __Hotfix0_GetTrackTypeVersion; // 0x10


	// RVA: 0x2f3887c VA: 0x759555087c
	public Void .ctor(LocalTrackStore store) { }
	// RVA: 0x2f3cc04 VA: 0x7595554c04
	public Boolean DoTrackTrigger(TrackTrigger trigger) { }
	// RVA: 0x2f3cca4 VA: 0x7595554ca4
	public Int64 GetTrackTypeVersion(String type) { }
}
```