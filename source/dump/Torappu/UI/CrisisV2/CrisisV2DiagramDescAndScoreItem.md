# CrisisV2DiagramDescAndScoreItem

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Text _score`

- `Text _desc`

- `UIAtlasImage _icon`

- `UIAtlasObject _atlasObject`

- `Tween m_scoreTween`

- `Int32 m_score`


## Methods

- `Void SetDescAndIcon(String, String)`

- `Void RenderScore(DescAndScoreInput)`

- `Int32 <RenderScore>b__8_0()`

- `Void <RenderScore>b__8_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2DiagramDescAndScoreItem : MonoBehaviour, IHotfixable
{
	private Text _score; // 0x18
	private Text _desc; // 0x20
	private UIAtlasImage _icon; // 0x28
	private UIAtlasObject _atlasObject; // 0x30
	private Tween m_scoreTween; // 0x38
	private Int32 m_score; // 0x40
	private static DelegateBridge __Hotfix0_SetDescAndIcon; // 0x0
	private static DelegateBridge __Hotfix0_RenderScore; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2bcd308 VA: 0x75951e5308
	public Void SetDescAndIcon(String desc, String iconName) { }
	// RVA: 0x2bcd408 VA: 0x75951e5408
	public Void RenderScore(DescAndScoreInput input) { }
	// RVA: 0x2bcd674 VA: 0x75951e5674
	public Void .ctor() { }
	// RVA: 0x2bcd6e4 VA: 0x75951e56e4
	private Int32 <RenderScore>b__8_0() { }
	// RVA: 0x2bcd6ec VA: 0x75951e56ec
	private Void <RenderScore>b__8_1(Int32 val) { }
}
```