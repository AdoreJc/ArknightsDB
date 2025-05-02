# EnemyHandbookShuffleSelectItem

**Namespace:** `Torappu.Scripts.UI.EnemyHandBook`


## Fields

- `Text _detailText`

- `Text _detailText2`

- `TwoStateToggle _toggle`

- `UIIntEvent onClick`

- `Int32 m_index`


## Methods

- `Void Render(Int32, String, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.EnemyHandBook
public class EnemyHandbookShuffleSelectItem : MonoBehaviour, IHotfixable
{
	private Text _detailText; // 0x18
	private Text _detailText2; // 0x20
	private TwoStateToggle _toggle; // 0x28
	public UIIntEvent onClick; // 0x30
	private Int32 m_index; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x376fb0c VA: 0x7595d87b0c
	public Void Render(Int32 index, String text, Boolean isSelected) { }
	// RVA: 0x376fbf4 VA: 0x7595d87bf4
	public Void OnClick() { }
	// RVA: 0x376fc88 VA: 0x7595d87c88
	public Void .ctor() { }
}
```