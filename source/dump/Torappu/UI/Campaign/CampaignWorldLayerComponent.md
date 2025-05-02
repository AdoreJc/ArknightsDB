# CampaignWorldLayerComponent

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignWorldLayer _layer`


## Properties

- `CampaignWorldLayer layer`


## Methods

- `CampaignWorldLayer get_layer()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldLayerComponent : MonoBehaviour, IHotfixable
{
	private CampaignWorldLayer _layer; // 0x18
	private static DelegateBridge __Hotfix0_get_layer; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public CampaignWorldLayer layer { get; }

	// RVA: 0x2dda4b4 VA: 0x75953f24b4
	public CampaignWorldLayer get_layer() { }
	// RVA: 0x2dda51c VA: 0x75953f251c
	public Void Start() { }
	// RVA: 0x2dda6a4 VA: 0x75953f26a4
	public Void .ctor() { }
}
```