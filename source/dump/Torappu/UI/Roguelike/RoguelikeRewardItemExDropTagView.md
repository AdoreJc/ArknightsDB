# RoguelikeRewardItemExDropTagView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Graphic _graphicBgLight`

- `Image _imgTagBg`

- `Text _txtTagName`


## Methods

- `Void Render(String, RoguelikeRewardExDropTagSrcType)`

- `String _GetExDropTagName(String, RoguelikeRewardExDropTagSrcType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardItemExDropTagView : MonoBehaviour, IHotfixable
{
	private Graphic _graphicBgLight; // 0x18
	private Image _imgTagBg; // 0x20
	private Text _txtTagName; // 0x28
	private List`1 _configs; // 0x30
	private static DelegateBridge __Hotfix0_GetGraphics; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__GetExDropTagName; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a9a408 VA: 0x75950b2408
	public List`1 GetGraphics() { }
	// RVA: 0x2a9a580 VA: 0x75950b2580
	public Void Render(String topicId, RoguelikeRewardExDropTagSrcType tagSrcType) { }
	// RVA: 0x2a9a768 VA: 0x75950b2768
	private String _GetExDropTagName(String topicId, RoguelikeRewardExDropTagSrcType tagSrcType) { }
	// RVA: 0x2a9a8c4 VA: 0x75950b28c4
	public Void .ctor() { }
}
```