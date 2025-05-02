# CampaignWorldLayerManager

**Namespace:** `Torappu.UI.Campaign`


## Methods

- `Void _SetComponentLayer(CampaignWorldLayerComponent)`

- `RectTransform _GetLayerTrans(CampaignWorldLayer)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldLayerManager : SingletonMonoBehaviour`1, IHotfixable
{
	private List`1 _layers; // 0x18
	private static DelegateBridge __Hotfix0_SetComponentLayer; // 0x0
	private static DelegateBridge __Hotfix0__SetComponentLayer; // 0x8
	private static DelegateBridge __Hotfix0__GetLayerTrans; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2dda584 VA: 0x75953f2584
	public static Void SetComponentLayer(CampaignWorldLayerComponent comp) { }
	// RVA: 0x2dda714 VA: 0x75953f2714
	private Void _SetComponentLayer(CampaignWorldLayerComponent comp) { }
	// RVA: 0x2dda84c VA: 0x75953f284c
	private RectTransform _GetLayerTrans(CampaignWorldLayer layer) { }
	// RVA: 0x2dda960 VA: 0x75953f2960
	public Void .ctor() { }
}
```