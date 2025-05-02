# SandboxV2CharSelectPluginHolder

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminCharSelectAbstractLeftView _leftView`

- `SandboxV2AdminCharAbstractShuffleView _shuffleView`

- `SandboxV2AdminCharAbstractEnsureView _ensureView`

- `SandboxV2AdminCharSelectAbstractPopView _popView`


## Methods

- `SandboxV2AdminCharSelectAbstractLeftView GetLeftView()`

- `SandboxV2AdminCharAbstractShuffleView GetShuffleView()`

- `SandboxV2AdminCharAbstractEnsureView GetEnsureView()`

- `SandboxV2AdminCharSelectAbstractPopView GetPopView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectPluginHolder : MonoBehaviour, IHotfixable
{
	private SandboxV2AdminCharSelectAbstractLeftView _leftView; // 0x18
	private SandboxV2AdminCharAbstractShuffleView _shuffleView; // 0x20
	private SandboxV2AdminCharAbstractEnsureView _ensureView; // 0x28
	private SandboxV2AdminCharSelectAbstractPopView _popView; // 0x30
	private static DelegateBridge __Hotfix0_GetLeftView; // 0x0
	private static DelegateBridge __Hotfix0_GetShuffleView; // 0x8
	private static DelegateBridge __Hotfix0_GetEnsureView; // 0x10
	private static DelegateBridge __Hotfix0_GetPopView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24878ec VA: 0x7594a9f8ec
	public SandboxV2AdminCharSelectAbstractLeftView GetLeftView() { }
	// RVA: 0x2487954 VA: 0x7594a9f954
	public SandboxV2AdminCharAbstractShuffleView GetShuffleView() { }
	// RVA: 0x24879bc VA: 0x7594a9f9bc
	public SandboxV2AdminCharAbstractEnsureView GetEnsureView() { }
	// RVA: 0x2487a24 VA: 0x7594a9fa24
	public SandboxV2AdminCharSelectAbstractPopView GetPopView() { }
	// RVA: 0x2487a8c VA: 0x7594a9fa8c
	public Void .ctor() { }
}
```