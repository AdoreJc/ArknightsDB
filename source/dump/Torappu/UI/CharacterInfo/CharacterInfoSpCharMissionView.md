# CharacterInfoSpCharMissionView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `RectTransform _splitPrefab`

- `RectTransform _splitContainer`

- `SimpleLayoutContent _layoutContent`

- `Boolean m_inited`

- `Adapter m_adapter`


## Methods

- `Void set_onJumpToClicked(Action`1)`

- `Void set_onGetRewardClicked(Action`1)`

- `Void Render(CharacterInfoSpCharMissionStateBean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSpCharMissionView : MonoBehaviour, IHotfixable
{
	private RectTransform _splitPrefab; // 0x18
	private RectTransform _splitContainer; // 0x20
	private SimpleLayoutContent _layoutContent; // 0x28
	private Boolean m_inited; // 0x30
	private Adapter m_adapter; // 0x38
	private Action`1 <onJumpToClicked>k__BackingField; // 0x40
	private Action`1 <onGetRewardClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onJumpToClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onJumpToClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onGetRewardClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onGetRewardClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onJumpToClicked { get; set; }
	public Action`1 onGetRewardClicked { get; set; }

	// RVA: 0x2d8af94 VA: 0x75953a2f94
	public Action`1 get_onJumpToClicked() { }
	// RVA: 0x2d8affc VA: 0x75953a2ffc
	public Void set_onJumpToClicked(Action`1 value) { }
	// RVA: 0x2d8b080 VA: 0x75953a3080
	public Action`1 get_onGetRewardClicked() { }
	// RVA: 0x2d8b0e8 VA: 0x75953a30e8
	public Void set_onGetRewardClicked(Action`1 value) { }
	// RVA: 0x2d8b16c VA: 0x75953a316c
	public Void Render(CharacterInfoSpCharMissionStateBean stateBean) { }
	// RVA: 0x2d8b2b4 VA: 0x75953a32b4
	private Void _InitIfNot() { }
	// RVA: 0x2d8b460 VA: 0x75953a3460
	public Void .ctor() { }
}
```