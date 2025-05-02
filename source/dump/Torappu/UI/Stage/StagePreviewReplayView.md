# StagePreviewReplayView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StagePreviewReplayViewObject _upPart`

- `StagePreviewReplayViewObject _downPart`

- `Animator _controlAnimator`

- `RectTransform _backRect`

- `Boolean m_inited`


## Methods

- `Void InitData(List`1, String)`

- `Void FadeOut()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewReplayView : MonoBehaviour, IHotfixable
{
	private StagePreviewReplayViewObject _upPart; // 0x18
	private StagePreviewReplayViewObject _downPart; // 0x20
	private Animator _controlAnimator; // 0x28
	private RectTransform _backRect; // 0x30
	private Boolean m_inited; // 0x38
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_FadeOut; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fabc10 VA: 0x75955c3c10
	public Void InitData(List`1 storyList, String stageId) { }
	// RVA: 0x2fac040 VA: 0x75955c4040
	public Void FadeOut() { }
	// RVA: 0x2fabe34 VA: 0x75955c3e34
	private Void _InitIfNot() { }
	// RVA: 0x2fac0d0 VA: 0x75955c40d0
	public Void .ctor() { }
}
```