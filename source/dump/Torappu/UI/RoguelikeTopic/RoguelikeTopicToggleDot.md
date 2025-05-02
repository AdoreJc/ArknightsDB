# RoguelikeTopicToggleDot

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIColorToggle _colorToggle`

- `UIAtlasImage _dotImg`

- `UIAtlasImage _completeDotImg`


## Properties

- `Boolean isOn`

- `Boolean isComplete`


## Methods

- `Boolean get_isOn()`

- `Void set_isOn(Boolean)`

- `Void set_isComplete(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicToggleDot : MonoBehaviour, IHotfixable
{
	private UIColorToggle _colorToggle; // 0x18
	private UIAtlasImage _dotImg; // 0x20
	private UIAtlasImage _completeDotImg; // 0x28
	private static DelegateBridge __Hotfix0_get_isOn; // 0x0
	private static DelegateBridge __Hotfix0_set_isOn; // 0x8
	private static DelegateBridge __Hotfix0_set_isComplete; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isOn { get; set; }
	public Boolean isComplete { set; }

	// RVA: 0x264c030 VA: 0x7594c64030
	public Boolean get_isOn() { }
	// RVA: 0x264c0a4 VA: 0x7594c640a4
	public Void set_isOn(Boolean value) { }
	// RVA: 0x264c130 VA: 0x7594c64130
	public Void set_isComplete(Boolean value) { }
	// RVA: 0x264c20c VA: 0x7594c6420c
	public Void .ctor() { }
}
```