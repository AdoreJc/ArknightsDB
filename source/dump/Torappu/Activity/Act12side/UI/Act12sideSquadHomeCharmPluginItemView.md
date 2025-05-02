# Act12sideSquadHomeCharmPluginItemView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Image _imgCharmItem`

- `Action m_onClickItem`

- `Single m_angle`

- `String m_charmId`


## Properties

- `Single Angle`

- `String charmId`


## Methods

- `Single get_Angle()`

- `String get_charmId()`

- `Void Render(String, Action, Single)`

- `Void OnCharmItemClick()`

- `Sprite _LoadIconSprite(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideSquadHomeCharmPluginItemView : MonoBehaviour, IHotfixable
{
	private Image _imgCharmItem; // 0x18
	private Action m_onClickItem; // 0x20
	private Single m_angle; // 0x28
	private String m_charmId; // 0x30
	private const Single ITEM_SCALE; // 0x0
	private static DelegateBridge __Hotfix0_get_Angle; // 0x0
	private static DelegateBridge __Hotfix0_get_charmId; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnCharmItemClick; // 0x18
	private static DelegateBridge __Hotfix0__LoadIconSprite; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Single Angle { get; }
	public String charmId { get; }

	// RVA: 0x34681e0 VA: 0x7595a801e0
	public Single get_Angle() { }
	// RVA: 0x3468248 VA: 0x7595a80248
	public String get_charmId() { }
	// RVA: 0x34682b0 VA: 0x7595a802b0
	public Void Render(String charmId, Action onClickItem, Single angle) { }
	// RVA: 0x3468540 VA: 0x7595a80540
	public Void OnCharmItemClick() { }
	// RVA: 0x34685c4 VA: 0x7595a805c4
	private Sprite _LoadIconSprite(String spriteId, String hubPath) { }
	// RVA: 0x34687d8 VA: 0x7595a807d8
	public Void .ctor() { }
}
```