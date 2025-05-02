# HandbookLockedView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `SimpleLayoutContent _content`

- `GameObject _unlockAllPart`

- `GameObject _lockedAllPart`

- `AnimationWrapper _wrapper`

- `GameObject _hasRewardPart`

- `GameObject _rewardPart`

- `SimpleLayoutContent _rewardContent`

- `Single _scale`

- `GameObject _titlePart`

- `Text _titleText`

- `GameObject _rewardTinyIcon`

- `Int32 index`

- `UIStringEvent onClickGroup`

- `HandbookUnlockAdapter m_adapter`

- `HandbookRewardAdapter m_rewardAdapter`

- `HandBookAvgGroupViewModel m_cacheViewModel`

- `Boolean m_isInited`

- `Boolean m_hasReward`


## Methods

- `Void _InitIfNot()`

- `Void OnEnable()`

- `Void SetText(String, DataUnlockType, String, String, String, String)`

- `Void SetTextSplit(String, DataUnlockType, String, String)`

- `Void OnAppear()`

- `Void DisAppearWithIndex(Int32)`

- `Void DisAppear()`

- `Void SetUnlockParam(List`1, List`1, String)`

- `Void SetText(String, DataUnlockType, List`1, String)`

- `Void SetAbleToUnlock(HandBookAvgGroupViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandbookLockedView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private GameObject _unlockAllPart; // 0x20
	private GameObject _lockedAllPart; // 0x28
	private AnimationWrapper _wrapper; // 0x30
	private GameObject _hasRewardPart; // 0x38
	private GameObject _rewardPart; // 0x40
	private SimpleLayoutContent _rewardContent; // 0x48
	private Single _scale; // 0x50
	private GameObject _titlePart; // 0x58
	private Text _titleText; // 0x60
	private GameObject _rewardTinyIcon; // 0x68
	public Int32 index; // 0x70
	public UIStringEvent onClickGroup; // 0x78
	public Action`1 onDetailShow; // 0x80
	private HandbookUnlockAdapter m_adapter; // 0x88
	private HandbookRewardAdapter m_rewardAdapter; // 0x90
	private HandBookAvgGroupViewModel m_cacheViewModel; // 0x98
	private Boolean m_isInited; // 0xa0
	private Boolean m_hasReward; // 0xa1
	private const String REWARD_SHOW; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_SetText; // 0x10
	private static DelegateBridge __Hotfix0_SetTextSplit; // 0x18
	private static DelegateBridge __Hotfix0_OnAppear; // 0x20
	private static DelegateBridge __Hotfix0_DisAppearWithIndex; // 0x28
	private static DelegateBridge __Hotfix0_DisAppear; // 0x30
	private static DelegateBridge __Hotfix0_SetUnlockParam; // 0x38
	private static DelegateBridge __Hotfix1_SetText; // 0x40
	private static DelegateBridge __Hotfix0_SetAbleToUnlock; // 0x48
	private static DelegateBridge __Hotfix0_OnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2eb04bc VA: 0x75954c84bc
	private Void _InitIfNot() { }
	// RVA: 0x2eb05f4 VA: 0x75954c85f4
	private Void OnEnable() { }
	// RVA: 0x2eb06ec VA: 0x75954c86ec
	public Void SetText(String charId, DataUnlockType type, String text, String param1, String param2, String param3) { }
	// RVA: 0x2eaf470 VA: 0x75954c7470
	public Void SetTextSplit(String charId, DataUnlockType type, String param, String overrideString) { }
	// RVA: 0x2eb09d0 VA: 0x75954c89d0
	public Void OnAppear() { }
	// RVA: 0x2eafe5c VA: 0x75954c7e5c
	public Void DisAppearWithIndex(Int32 openIndex) { }
	// RVA: 0x2eb065c VA: 0x75954c865c
	public Void DisAppear() { }
	// RVA: 0x2eafc10 VA: 0x75954c7c10
	public Void SetUnlockParam(List`1 paramList, List`1 rewardList, String title) { }
	// RVA: 0x2eaf7a8 VA: 0x75954c77a8
	public Void SetText(String charId, DataUnlockType type, List`1 param, String overrideString) { }
	// RVA: 0x2eafab0 VA: 0x75954c7ab0
	public Void SetAbleToUnlock(HandBookAvgGroupViewModel viewModel) { }
	// RVA: 0x2eb0ac0 VA: 0x75954c8ac0
	public Void OnClick() { }
	// RVA: 0x2eb0b68 VA: 0x75954c8b68
	public Void .ctor() { }
}
```