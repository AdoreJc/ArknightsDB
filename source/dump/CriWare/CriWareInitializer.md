# CriWareInitializer

**Namespace:** `CriWare`


## Fields

- `Boolean initializesFileSystem`

- `CriFsConfig fileSystemConfig`

- `Boolean initializesAtom`

- `CriAtomConfig atomConfig`

- `Boolean initializesMana`

- `CriManaConfig manaConfig`

- `Boolean useDecrypter`

- `Config DecrypterConfig`

- `Boolean dontInitializeOnAwake`

- `Boolean dontDestroyOnLoad`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void Initialize()`

- `Void Shutdown()`

- `Void OnValidate()`

- `Void ValidateConfigEditorForNotPublic()`

- `Void ValidateConfigForNotPublic()`

- `Void ValidateConfigEditor()`

- `Void ValidateConfig()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriWareInitializer : CriMonoBehaviour
{
	public Boolean initializesFileSystem; // 0x28
	public CriFsConfig fileSystemConfig; // 0x30
	public Boolean initializesAtom; // 0x38
	public CriAtomConfig atomConfig; // 0x40
	public Boolean initializesMana; // 0x48
	public CriManaConfig manaConfig; // 0x50
	public Boolean useDecrypter; // 0x58
	public Config DecrypterConfig; // 0x60
	public Boolean dontInitializeOnAwake; // 0x68
	public Boolean dontDestroyOnLoad; // 0x69
	private static Int32 initializationCount; // 0x0


	// RVA: 0x414af04 VA: 0x7596762f04
	protected override Void OnEnable() { }
	// RVA: 0x414af08 VA: 0x7596762f08
	private Void Start() { }
	// RVA: 0x414af0c VA: 0x7596762f0c
	private Void OnDestroy() { }
	// RVA: 0x414b024 VA: 0x7596763024
	public override Void CriInternalUpdate() { }
	// RVA: 0x414b028 VA: 0x7596763028
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x414b02c VA: 0x759676302c
	public Void Initialize() { }
	// RVA: 0x414af10 VA: 0x7596762f10
	public Void Shutdown() { }
	// RVA: 0x414ba2c VA: 0x7596763a2c
	public static Boolean IsInitialized() { }
	// RVA: 0x414ba8c VA: 0x7596763a8c
	public static Void AddAudioEffectInterface(IntPtr effect_interface) { }
	// RVA: 0x414b380 VA: 0x7596763380
	public static Boolean InitializeFileSystem(CriFsConfig config) { }
	// RVA: 0x414b494 VA: 0x7596763494
	public static Boolean InitializeAtom(CriAtomConfig config) { }
	// RVA: 0x414b968 VA: 0x7596763968
	public static Boolean InitializeMana(CriManaConfig config) { }
	// RVA: 0x414bb6c VA: 0x7596763b6c
	private Void OnValidate() { }
	// RVA: 0x414bb74 VA: 0x7596763b74
	private Void ValidateConfigEditorForNotPublic() { }
	// RVA: 0x414bbf4 VA: 0x7596763bf4
	private Void ValidateConfigForNotPublic() { }
	// RVA: 0x414bb70 VA: 0x7596763b70
	private Void ValidateConfigEditor() { }
	// RVA: 0x414b37c VA: 0x759676337c
	private Void ValidateConfig() { }
	// RVA: 0x414bbf8 VA: 0x7596763bf8
	public Void .ctor() { }
}
```