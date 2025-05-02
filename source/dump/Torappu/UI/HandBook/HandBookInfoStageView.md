# HandBookInfoStageView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `SimpleLayoutContent _unlockContent`

- `SimpleLayoutContent _itemContent`

- `UIBlurFloatPanel _blurFloatPanel`

- `Single _scale`

- `HandbookRewardAdapter m_rewardAdapter`

- `HandbookUnlockAdapter m_unlockAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(HandBookStageViewModel)`

- `Void Show()`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStageView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _unlockContent; // 0x18
	private SimpleLayoutContent _itemContent; // 0x20
	private UIBlurFloatPanel _blurFloatPanel; // 0x28
	private Single _scale; // 0x30
	private HandbookRewardAdapter m_rewardAdapter; // 0x38
	private HandbookUnlockAdapter m_unlockAdapter; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2eaeb88 VA: 0x75954c6b88
	private Void _InitIfNot() { }
	// RVA: 0x2ea3e28 VA: 0x75954bbe28
	public Void Render(HandBookStageViewModel stage) { }
	// RVA: 0x2ea3f04 VA: 0x75954bbf04
	public Void Show() { }
	// RVA: 0x2eaed54 VA: 0x75954c6d54
	public Void Hide() { }
	// RVA: 0x2eaedc8 VA: 0x75954c6dc8
	public Void .ctor() { }
}
```