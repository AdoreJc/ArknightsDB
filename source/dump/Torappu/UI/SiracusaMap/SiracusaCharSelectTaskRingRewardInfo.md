# SiracusaCharSelectTaskRingRewardInfo

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String taskRingId`

- `UIItemViewModel item`

- `Boolean hasGet`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectTaskRingRewardInfo : IHotfixable
{
	public String taskRingId; // 0x10
	public UIItemViewModel item; // 0x18
	public Boolean hasGet; // 0x20
	private static DelegateBridge __Hotfix0_CreateInfo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x23f3f10 VA: 0x7594a0bf10
	public static SiracusaCharSelectTaskRingRewardInfo CreateInfo(String ringId, ItemBundle item, Boolean hasGet) { }
	// RVA: 0x23f4020 VA: 0x7594a0c020
	public Void .ctor() { }
}
```