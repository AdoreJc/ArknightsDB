# StackTrace

**Namespace:** `System.Diagnostics`


## Fields

- `Boolean debug_info`


## Methods

- `Void init_frames(Int32, Boolean)`

- `Boolean AddFrames(StringBuilder, Boolean, out)`

- `Void GetFullNameForStackTrace(StringBuilder, MethodBase, Boolean, out, out)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Diagnostics
public class StackTrace
{
	public const Int32 METHODS_TO_SKIP; // 0x0
	private const String prefix; // 0x0
	private StackFrame[] frames; // 0x10
	private readonly StackTrace[] captured_traces; // 0x18
	private Boolean debug_info; // 0x20
	private static Boolean isAotidSet; // 0x0
	private static String aotid; // 0x8

	public virtual Int32 FrameCount { get; }

	// RVA: 0x6079b58 VA: 0x7598691b58
	public Void .ctor() { }
	// RVA: 0x6079d88 VA: 0x7598691d88
	public Void .ctor(Boolean fNeedFileInfo) { }
	// RVA: 0x6079db8 VA: 0x7598691db8
	public Void .ctor(Int32 skipFrames, Boolean fNeedFileInfo) { }
	// RVA: 0x6079b7c VA: 0x7598691b7c
	private Void init_frames(Int32 skipFrames, Boolean fNeedFileInfo) { }
	// RVA: 0x6079dec VA: 0x7598691dec
	private static StackFrame[] get_trace(Exception e, Int32 skipFrames, Boolean fNeedFileInfo) { }
	// RVA: 0x6079df4 VA: 0x7598691df4
	public Void .ctor(Exception e, Boolean fNeedFileInfo) { }
	// RVA: 0x6079e00 VA: 0x7598691e00
	public Void .ctor(Exception e, Int32 skipFrames, Boolean fNeedFileInfo) { }
	// RVA: 0x6079f00 VA: 0x7598691f00
	public virtual Int32 get_FrameCount() { }
	// RVA: 0x6079f18 VA: 0x7598691f18
	public virtual StackFrame GetFrame(Int32 index) { }
	// RVA: 0x6079f78 VA: 0x7598691f78
	private static String GetAotId() { }
	// RVA: 0x607a048 VA: 0x7598692048
	private Boolean AddFrames(StringBuilder sb, Boolean separator, out Boolean isAsync) { }
	// RVA: 0x607a4f8 VA: 0x75986924f8
	private Void GetFullNameForStackTrace(StringBuilder sb, MethodBase mi, Boolean needsNewLine, out Boolean skipped, out Boolean isAsync) { }
	// RVA: 0x607ab50 VA: 0x7598692b50
	private static Void ConvertAsyncStateMachineMethod(ref MethodBase method, ref Type declaringType) { }
	// RVA: 0x607afc0 VA: 0x7598692fc0
	public override String ToString() { }
	// RVA: 0x607b11c VA: 0x759869311c
	internal String ToString(TraceFormat traceFormat) { }
}
```