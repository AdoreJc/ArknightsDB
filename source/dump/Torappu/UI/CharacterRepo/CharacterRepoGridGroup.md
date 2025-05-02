# CharacterRepoGridGroup

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `CharacterRepoGridAdapter _dataTarget`

- `LoopHorizontalScrollRect _scrollRect`

- `GameObject _emptyStatePanel`

- `UICharacterCardSelectEvent cardStarMarkEvent`

- `Params m_charCardParams`

- `Single m_scrollPosCache`

- `Boolean m_scrollPosLock`

- `Int32 m_scrollPosRetryCount`


## Methods

- `Void Init(Options)`

- `IEnumerator _TrySetScrollPosition(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoGridGroup : DataBinder`1
{
	private CharacterRepoGridAdapter _dataTarget; // 0x20
	private LoopHorizontalScrollRect _scrollRect; // 0x28
	private GameObject _emptyStatePanel; // 0x30
	private UICharacterCardSelectEvent cardStarMarkEvent; // 0x38
	private Params m_charCardParams; // 0x40
	private Single m_scrollPosCache; // 0x50
	private Boolean m_scrollPosLock; // 0x54
	private Int32 m_scrollPosRetryCount; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__TrySetScrollPosition; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2cfa518 VA: 0x7595312518
	public Void Init(Options options) { }
	// RVA: 0x2cfe4c8 VA: 0x75953164c8
	public override Void OnValueChanged(CharacterRepoCardGroupViewProperty property) { }
	// RVA: 0x2cfe76c VA: 0x759531676c
	private IEnumerator _TrySetScrollPosition(Single scrollPos) { }
	// RVA: 0x2cfe858 VA: 0x7595316858
	public Void .ctor() { }
}
```