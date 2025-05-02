# RoguelikeSquadView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeSquadItem _item`

- `UIIntStringEvent _onClickSkill`

- `UIIntEvent _onCharClick`

- `UIIntEvent _onPosClick`

- `Text _squadCount`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int32, Int32, List`1)`

- `Void InjectPlugin(IRoguelikeCharCardPlugin)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSquadView : MonoBehaviour, IHotfixable
{
	private RoguelikeSquadItem _item; // 0x18
	private List`1 _itemContainer; // 0x20
	private UIIntStringEvent _onClickSkill; // 0x28
	private UIIntEvent _onCharClick; // 0x30
	private UIIntEvent _onPosClick; // 0x38
	private Text _squadCount; // 0x40
	private List`1 m_itemList; // 0x48
	private List`1 m_plugins; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2af88dc VA: 0x75951108dc
	private Void _InitIfNot() { }
	// RVA: 0x2af336c VA: 0x759510b36c
	public Void Render(Int32 totalCount, Int32 troopCount, List`1 viewModelList) { }
	// RVA: 0x2af2e6c VA: 0x759510ae6c
	public Void InjectPlugin(IRoguelikeCharCardPlugin plugin) { }
	// RVA: 0x2af8b24 VA: 0x7595110b24
	public Void .ctor() { }
}
```