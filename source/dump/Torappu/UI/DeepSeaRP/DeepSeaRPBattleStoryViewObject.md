# DeepSeaRPBattleStoryViewObject

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Text _textTime`

- `Text _textStageCode`

- `CanvasGroup _canvasGroup`

- `GameObject _btnPanel`


## Methods

- `Void Render(StageViewModel, StoryData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattleStoryViewObject : MonoBehaviour, IHotfixable
{
	private Text _textTime; // 0x18
	private Text _textStageCode; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private GameObject _btnPanel; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29c1674 VA: 0x7594fd9674
	public Void Render(StageViewModel stageModel, StoryData storyData) { }
	// RVA: 0x29c2270 VA: 0x7594fda270
	public Void .ctor() { }
}
```