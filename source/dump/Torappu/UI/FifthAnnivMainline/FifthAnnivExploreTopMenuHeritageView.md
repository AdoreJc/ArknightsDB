# FifthAnnivExploreTopMenuHeritageView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `TwoStateToggle _emptyHeritageToogle`

- `UIAtlasImage _groupIconImg`

- `UIAtlasObject _groupIconAtlas`

- `Text _groupNameText`

- `GameObject _heritageSelectObj`

- `Action <onBtnClick>k__BackingField`


## Properties

- `Action onBtnClick`


## Methods

- `Void set_onBtnClick(Action)`

- `Action get_onBtnClick()`

- `Void Render(FifthAnnivExploreGroupHeritageViewModel)`

- `Void OnBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreTopMenuHeritageView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _emptyHeritageToogle; // 0x18
	private UIAtlasImage _groupIconImg; // 0x20
	private UIAtlasObject _groupIconAtlas; // 0x28
	private Text _groupNameText; // 0x30
	private GameObject _heritageSelectObj; // 0x38
	private Action <onBtnClick>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_set_onBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onBtnClick { get; set; }

	// RVA: 0x29326a8 VA: 0x7594f4a6a8
	public Void set_onBtnClick(Action value) { }
	// RVA: 0x293272c VA: 0x7594f4a72c
	private Action get_onBtnClick() { }
	// RVA: 0x2932794 VA: 0x7594f4a794
	public Void Render(FifthAnnivExploreGroupHeritageViewModel viewModel) { }
	// RVA: 0x29329c0 VA: 0x7594f4a9c0
	public Void OnBtnClick() { }
	// RVA: 0x2932a5c VA: 0x7594f4aa5c
	public Void .ctor() { }
}
```