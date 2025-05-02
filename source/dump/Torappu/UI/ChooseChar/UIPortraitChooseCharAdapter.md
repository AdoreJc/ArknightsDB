# UIPortraitChooseCharAdapter

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `GameObject _prefabCharCard`

- `RectTransform _container`


## Methods

- `Void set_selectCharIdList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIPortraitChooseCharAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _prefabCharCard; // 0x58
	private RectTransform _container; // 0x60
	private List`1 <selectCharIdList>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_selectCharIdList; // 0x0
	private static DelegateBridge __Hotfix0_set_selectCharIdList; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private List`1 selectCharIdList { get; set; }

	// RVA: 0x2c3d88c VA: 0x759525588c
	private List`1 get_selectCharIdList() { }
	// RVA: 0x2c3d8f4 VA: 0x75952558f4
	public Void set_selectCharIdList(List`1 value) { }
	// RVA: 0x2c3d978 VA: 0x7595255978
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2c3da38 VA: 0x7595255a38
	public override Void UpdateView(Int32 position, GameObject viewObj, ViewHolder holder, UIPortraitChooseCharCardViewModel data) { }
	// RVA: 0x2c3ddac VA: 0x7595255dac
	public Void .ctor() { }
}
```