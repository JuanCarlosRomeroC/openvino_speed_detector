python3 /opt/intel/openvino_2020.3.194/deployment_tools/model_optimizer/mo_tf.py \
--input_model /home/eva/test/tensorflow-yolov3/yolov3_coco_yidong.pb \
--tensorflow_use_custom_operations_config /opt/intel/openvino_2020.3.194/deployment_tools/model_optimizer/extensions/front/tf/yolo_v3.json \
--batch 1


python3 mo_tf.py \
--input_model /home/eva/test/tensorflow-yolo-v3/frozen_darknet_tiny_yolov3_model.pb \
--tensorflow_use_custom_operations_config /opt/intel/openvino_2020.3.194/deployment_tools/model_optimizer/extensions/front/tf/yolo_v3_tiny.json \
--batch 1