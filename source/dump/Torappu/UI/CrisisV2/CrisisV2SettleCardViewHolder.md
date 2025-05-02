# CrisisV2SettleCardViewHolder

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `GameObject _objEmptyBg`

- `CrisisV2SettleCardView m_cardView`

- `Boolean m_hasInited`


## Methods

- `Void Render(SquadItemStruct, CrisisV2SettleCardView, Boolean)`

- `Void RenderNoDetailAssist(SquadSkinInfo, CrisisV2SettleCardView, Boolean)`

- `Void _InitIfNot(CrisisV2SettleCardView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleCardViewHolder : MonoBehaviour, IHotfixable
{
	private GameObject _objEmptyBg; // 0x18
	private CrisisV2SettleCardView m_cardView; // 0x20
	private Boolean m_hasInited; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderNoDetailAssist; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2bd0238 VA: 0x75951e8238
	public Void Render(SquadItemStruct viewModel, CrisisV2SettleCardView prefab, Boolean isAssist) { }
	// RVA: 0x2bd04f4 VA: 0x75951e84f4
	public Void RenderNoDetailAssist(SquadSkinInfo skinInfo, CrisisV2SettleCardView prefab, Boolean isAssist) { }
	// RVA: 0x2bd03f4 VA: 0x75951e83f4
	private Void _InitIfNot(CrisisV2SettleCardView prefab) { }
	// RVA: 0x2bd06b0 VA: 0x75951e86b0
	public Void .ctor() { }
}
```