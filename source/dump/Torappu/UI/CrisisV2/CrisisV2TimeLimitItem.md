# CrisisV2TimeLimitItem

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Single _cardScale`

- `RectTransform _cardRoot`

- `GameObject _remainTimeObject`

- `GameObject _itemObject`

- `Text _textTime`

- `Boolean m_isInited`

- `UIItemCard m_uiItemCard`


## Methods

- `Void Render(CrisisV2TimeLimitItemModel, Boolean)`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__8_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2TimeLimitItem : MonoBehaviour, IHotfixable
{
	private Single _cardScale; // 0x18
	private RectTransform _cardRoot; // 0x20
	private GameObject _remainTimeObject; // 0x28
	private GameObject _itemObject; // 0x30
	private Text _textTime; // 0x38
	private Boolean m_isInited; // 0x40
	private UIItemCard m_uiItemCard; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c1a9ec VA: 0x75952329ec
	public Void Render(CrisisV2TimeLimitItemModel timeLimitItem, Boolean isClaimed) { }
	// RVA: 0x2c1abd4 VA: 0x7595232bd4
	private Void _InitIfNot() { }
	// RVA: 0x2c1ae30 VA: 0x7595232e30
	public Void .ctor() { }
	// RVA: 0x2c1aea8 VA: 0x7595232ea8
	private Void <_InitIfNot>b__8_0(Int32 _) { }
}
```