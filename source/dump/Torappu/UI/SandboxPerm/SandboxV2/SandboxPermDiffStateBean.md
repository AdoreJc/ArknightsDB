# SandboxPermDiffStateBean

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxPermDiffGroupProperty property`

- `String topicId`


## Methods

- `String GetModelName(Int32)`

- `Void InitData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxPermDiffStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public SandboxPermDiffGroupProperty property; // 0x18
	public String topicId; // 0x20
	private static DelegateBridge __Hotfix0_GetModelName; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24814c0 VA: 0x7594a994c0
	public String GetModelName(Int32 mode) { }
	// RVA: 0x247e73c VA: 0x7594a9673c
	public Void InitData(String i_topicId) { }
	// RVA: 0x2481724 VA: 0x7594a99724
	public Void .ctor() { }
}
```