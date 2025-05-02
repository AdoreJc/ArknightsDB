# StageMixStoryRetroLineItemView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `UIDynImage _titleImage`

- `UIAnimationLocation _positionAnimation`

- `Int32 _positionDistance`

- `Single m_positionAnimationLength`

- `UIStateFinder m_finder`

- `String m_cachedStorySetId`

- `String m_cachedIconId`


## Properties

- `Single focusDuration`


## Methods

- `Single get_focusDuration()`

- `Void OnClickEvent()`

- `Void Render(StageStorylineStorySetViewModel)`

- `Void ApplyDistance(Single)`

- `Void _GetAnimationLengthIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryRetroLineItemView : MonoBehaviour, IHotfixable
{
	private UIDynImage _titleImage; // 0x18
	private UIAnimationLocation _positionAnimation; // 0x20
	private Int32 _positionDistance; // 0x30
	private Single m_positionAnimationLength; // 0x34
	private UIStateFinder m_finder; // 0x38
	private String m_cachedStorySetId; // 0x48
	private String m_cachedIconId; // 0x50
	private static DelegateBridge __Hotfix0_get_focusDuration; // 0x0
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDistance; // 0x18
	private static DelegateBridge __Hotfix0__GetAnimationLengthIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Single focusDuration { get; }

	// RVA: 0x2ffedbc VA: 0x7595616dbc
	public Single get_focusDuration() { }
	// RVA: 0x2ffef0c VA: 0x7595616f0c
	public Void OnClickEvent() { }
	// RVA: 0x2ffeff8 VA: 0x7595616ff8
	public Void Render(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fff120 VA: 0x7595617120
	public Void ApplyDistance(Single signedDistance) { }
	// RVA: 0x2ffee34 VA: 0x7595616e34
	private Void _GetAnimationLengthIfNot() { }
	// RVA: 0x2fff244 VA: 0x7595617244
	public Void .ctor() { }
}
```