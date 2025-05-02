# SandboxV2CircleProgressBar

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UISlicedCircleBar _totalCircleBar`

- `UISlicedCircleBar _currCircleBar`

- `Single _startAngle`

- `Single _maxAngleSpan`


## Methods

- `Void Awake()`

- `Void SetColor(Color)`

- `Void SetProgress(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CircleProgressBar : MonoBehaviour, IHotfixable
{
	private UISlicedCircleBar _totalCircleBar; // 0x18
	private UISlicedCircleBar _currCircleBar; // 0x20
	private Single _startAngle; // 0x28
	private Single _maxAngleSpan; // 0x2c
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_SetColor; // 0x8
	private static DelegateBridge __Hotfix0_SetProgress; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x24fe060 VA: 0x7594b16060
	private Void Awake() { }
	// RVA: 0x24fe100 VA: 0x7594b16100
	public Void SetColor(Color color) { }
	// RVA: 0x24fe1c4 VA: 0x7594b161c4
	public Void SetProgress(Single progress) { }
	// RVA: 0x24fe254 VA: 0x7594b16254
	public Void .ctor() { }
}
```