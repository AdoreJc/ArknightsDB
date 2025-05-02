# SandboxV2ToolSelectItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _selectGo`

- `Text _textSelectIndex`

- `SandboxV2SquadToolItemView _toolItemPrefab`

- `RectTransform _toolItemRoot`

- `SandboxV2SquadToolItemView m_toolItemView`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Int32, SandboxV2SquadToolModel, Boolean, Boolean, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ToolSelectItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectGo; // 0x18
	private Text _textSelectIndex; // 0x20
	private SandboxV2SquadToolItemView _toolItemPrefab; // 0x28
	private RectTransform _toolItemRoot; // 0x30
	private Action`1 <onItemClick>k__BackingField; // 0x38
	private SandboxV2SquadToolItemView m_toolItemView; // 0x40
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Action`1 onItemClick { get; set; }

	// RVA: 0x2622280 VA: 0x7594c3a280
	private Action`1 get_onItemClick() { }
	// RVA: 0x26222e8 VA: 0x7594c3a2e8
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x262236c VA: 0x7594c3a36c
	public Void Render(Int32 position, SandboxV2SquadToolModel toolModel, Boolean isSelect, Boolean showIndex, Int32 selectIdx) { }
	// RVA: 0x2622594 VA: 0x7594c3a594
	public Void .ctor() { }
}
```