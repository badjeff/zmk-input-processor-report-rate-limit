# Copyright (c) 2023 The ZMK Contributors
# SPDX-License-Identifier: MIT

target_sources_ifdef(CONFIG_ZMK_INPUT_PROCESSOR_REPORT_RATE_LIMIT app PRIVATE input_processor_report_rate_limit.c)
