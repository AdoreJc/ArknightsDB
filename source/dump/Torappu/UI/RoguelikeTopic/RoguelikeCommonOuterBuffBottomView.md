# RoguelikeCommonOuterBuffBottomView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeCommonOuterBuffBottomIconView _iconView`

- `GameObject _normalPanel`

- `GameObject _difficultPanel`

- `RoguelikeCommonOuterBuffBottomDifficultyView _diffView`

- `RoguelikeCommonOuterBuffBottomNormalView _normalView`

- `Boolean m_isInited`

- `RoguelikeCommonOuterBuffNodeBaseViewModel m_cachedNodeViewModel`


## Methods

- `Void Render(RoguelikeCommonOuterBuffViewModel, RoguelikeCommonOuterBuffNodeBaseViewModel)`

- `Void OnConfirmUpgrade()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffBottomView : MonoBehaviour, IHotfixable
{
	private RoguelikeCommonOuterBuffBottomIconView _iconView; // 0x18
	private GameObject _normalPanel; // 0x20
	private GameObject _difficultPanel; // 0x28
	private RoguelikeCommonOuterBuffBottomDifficultyView _diffView; // 0x30
	private RoguelikeCommonOuterBuffBottomNormalView _normalView; // 0x38
	public Action`1 onConfirmUpgrade; // 0x40
	private Boolean m_isInited; // 0x48
	private RoguelikeCommonOuterBuffNodeBaseViewModel m_cachedNodeViewModel; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirmUpgrade; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x265d668 VA: 0x7594c75668
	public Void Render(RoguelikeCommonOuterBuffViewModel viewModel, RoguelikeCommonOuterBuffNodeBaseViewModel nodeViewModel) { }
	// RVA: 0x265d898 VA: 0x7594c75898
	public Void OnConfirmUpgrade() { }
	// RVA: 0x265d938 VA: 0x7594c75938
	public Void .ctor() { }
}
```