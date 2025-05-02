# StageRankViewViaSwitch

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIColorGraphic _rankColorGraph`

- `Boolean m_isInited`

- `Int32 m_rankCache`


## Properties

- `UIColorGraphic rankColorGraph`


## Methods

- `UIColorGraphic get_rankColorGraph()`

- `Void _InitIfNot()`

- `Void Render(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRankViewViaSwitch : MonoBehaviour
{
	private RankPair[] _ranks; // 0x18
	private UIColorGraphic _rankColorGraph; // 0x20
	private Boolean m_isInited; // 0x28
	private Int32 m_rankCache; // 0x2c

	public UIColorGraphic rankColorGraph { get; }

	// RVA: 0x2faca14 VA: 0x75955c4a14
	public UIColorGraphic get_rankColorGraph() { }
	// RVA: 0x2faca1c VA: 0x75955c4a1c
	private Void _InitIfNot() { }
	// RVA: 0x2fa263c VA: 0x75955ba63c
	public Void Render(Int32 rank) { }
	// RVA: 0x2faca34 VA: 0x75955c4a34
	public Void .ctor() { }
}
```