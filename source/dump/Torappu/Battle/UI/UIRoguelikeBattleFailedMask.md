# UIRoguelikeBattleFailedMask

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIAtlasObject _atlas`

- `UIAtlasImage _icon`

- `Text _title`

- `Single _fadeinDuration`

- `CanvasGroup m_canvasGroup`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIRoguelikeBattleFailedMask : MonoBehaviour, IHotfixable
{
	protected UIAtlasObject _atlas; // 0x18
	protected UIAtlasImage _icon; // 0x20
	protected Text _title; // 0x28
	protected List`1 _textHints; // 0x30
	protected Single _fadeinDuration; // 0x38
	protected readonly Int32 HINT_COUNT; // 0x3c
	protected readonly String HINT_PREFIX; // 0x40
	protected CanvasGroup m_canvasGroup; // 0x48
	private static DelegateBridge __Hotfix0_OnPanelClick; // 0x0
	private static DelegateBridge __Hotfix0_BattleFailedPanelHide; // 0x8
	private static DelegateBridge __Hotfix0_BattleFailedPanelInit; // 0x10
	private static DelegateBridge __Hotfix0_BattleFailedPanelShow; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20728f0 VA: 0x759468a8f0
	public virtual Void OnPanelClick() { }
	// RVA: 0x20729d4 VA: 0x759468a9d4
	public virtual Boolean BattleFailedPanelHide() { }
	// RVA: 0x2072a5c VA: 0x759468aa5c
	public virtual RectTransform BattleFailedPanelInit() { }
	// RVA: 0x2072b2c VA: 0x759468ab2c
	public virtual Boolean BattleFailedPanelShow(String topicId, RoguelikeTopicMode mode) { }
	// RVA: 0x2073208 VA: 0x759468b208
	public Void .ctor() { }
}
```