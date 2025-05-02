# MainMissionProgressItem

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Text _processTargetLabel`

- `Text _processValueLabel`

- `Image _barImg`

- `MissionProgressBar _progressBar`


## Methods

- `Void Render(Int32, Int32)`

- `Void ApplyBarStyle(Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MainMissionProgressItem : MonoBehaviour, IHotfixable
{
	private Text _processTargetLabel; // 0x18
	private Text _processValueLabel; // 0x20
	private Image _barImg; // 0x28
	private MissionProgressBar _progressBar; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ApplyBarStyle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x273cb34 VA: 0x7594d54b34
	public Void Render(Int32 target, Int32 value) { }
	// RVA: 0x273cc38 VA: 0x7594d54c38
	public Void ApplyBarStyle(Color barColor) { }
	// RVA: 0x273ccfc VA: 0x7594d54cfc
	public Void .ctor() { }
}
```