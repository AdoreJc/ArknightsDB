# ZoneRecordAllRewardItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SimpleLayoutContent _easyRewards`

- `SimpleLayoutContent _normalRewards`

- `SimpleLayoutContent _toughRewards`

- `Text _recordName`

- `GameObject _lightBg`

- `GameObject _darkBg`

- `Single _itemCardScaler`


## Methods

- `Void Render(ZoneRecordViewModel, Int32)`

- `Void _RenderReward(ZoneRecordRewardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordAllRewardItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _easyRewards; // 0x18
	private SimpleLayoutContent _normalRewards; // 0x20
	private SimpleLayoutContent _toughRewards; // 0x28
	private Text _recordName; // 0x30
	private GameObject _lightBg; // 0x38
	private GameObject _darkBg; // 0x40
	private Single _itemCardScaler; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderReward; // 0x8
	private static DelegateBridge __Hotfix0__GenRewardViewModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fc39b0 VA: 0x75955db9b0
	public Void Render(ZoneRecordViewModel viewModel, Int32 idx) { }
	// RVA: 0x2fc3c40 VA: 0x75955dbc40
	private Void _RenderReward(ZoneRecordRewardViewModel rewardViewModel) { }
	// RVA: 0x2fc3d78 VA: 0x75955dbd78
	private List`1 _GenRewardViewModel(ItemBundle[] items) { }
	// RVA: 0x2fc3f4c VA: 0x75955dbf4c
	public Void .ctor() { }
}
```