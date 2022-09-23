# Build onnxruntime library

## for Mac OS
> $ git clone https://github.com/microsoft/onnxruntime --recursive

> $ cd onnxruntime

> $ ./build.sh --config MinSizeRel --build_shared_lib --parallel  --osx_arch arm64 --build_wheel

## convert models from onnx to ort format
> $ pip3 install onnxruntime onnx

> $ python3  -m onnxruntime.tools.convert_onnx_models_to_ort models/

## for Iphone Simulator
> $ ./build.sh --config Release --use_xcode --ios --ios_sysroot iphonesimulator --osx_arch arm64 --apple_deploy_target 13.0 --disable_exceptions --include_ops_by_config ~/models/required_operators.config --skip_tests