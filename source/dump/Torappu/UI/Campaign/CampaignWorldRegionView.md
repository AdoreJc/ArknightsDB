# CampaignWorldRegionView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `ParticleSystem _constantFog`

- `ParticleSystem _disappearFog`


## Methods

- `Void Render(CampaignWorldRegionViewModel)`

- `Void PlayFogDisappear()`

- `Void StopEffect()`

- `Void _ApplyHolderConfig()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldRegionView : MonoBehaviour, IHotfixable
{
	private const String FOG_MATERIAL_COLOR_PROPERTY; // 0x0
	private const Int32 PIXEL_PER_UNIT; // 0x0
	private const Single FADE_DURATION; // 0x0
	private ParticleSystem _constantFog; // 0x18
	private ParticleSystem _disappearFog; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayFogDisappear; // 0x8
	private static DelegateBridge __Hotfix0_StopEffect; // 0x10
	private static DelegateBridge __Hotfix0__ApplyHolderConfig; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2dd4b00 VA: 0x75953ecb00
	public Void Render(CampaignWorldRegionViewModel viewModel) { }
	// RVA: 0x2dd4c0c VA: 0x75953ecc0c
	public Void PlayFogDisappear() { }
	// RVA: 0x2dd4e20 VA: 0x75953ece20
	public Void StopEffect() { }
	// RVA: 0x2dd4eb4 VA: 0x75953eceb4
	private Void _ApplyHolderConfig() { }
	// RVA: 0x2dd5678 VA: 0x75953ed678
	public Void Awake() { }
	// RVA: 0x2dd56e0 VA: 0x75953ed6e0
	public Void .ctor() { }
}
```