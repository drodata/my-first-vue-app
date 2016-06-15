<template>
    <vux-tab></vux-tab>
    <div class="vux">
        <divider>Flexbox</divider>
        <flexbox style="height:40px;">
            <flexbox-item>
                <div class="flex-demo">1</div>
            </flexbox-item>
            <flexbox-item>
                <div class="flex-demo">2</div>
            </flexbox-item>
        </flexbox>

        <group>
            <cell title="vue" value="cool"></cell>
        </group>
        <group>
            <cell title="vue">
                <div class="badge-value">
                    New Message
                    <badge text="8"></badge>
                </div>
            </cell>
        </group>
        <icon type="success"></icon>
        <divider>Address</divider>

    </div>
</template>

<script>
import Flexbox from 'vux-components/flexbox'
import FlexboxItem from 'vux-components/flexbox-item'
import Group from 'vux-components/group'
import Cell from 'vux-components/cell'
import Icon from 'vux-components/icon'
import Badge from 'vux-components/badge'
import Divider from 'vux-components/divider'

import VuxTab from './VuxTab'

export default {
  components: { Group, Cell, Icon, Badge, Divider, Flexbox, FlexboxItem, VuxTab }
}
</script>

<style>
@import '~vux/dist/vux.css';

.flex-demo {
  text-align: center;
  color: #fff;
  background-color: #20b907;
  margin-bottom: 8px;
  border-radius: 4px;
  -webkit-background-clip: padding-box;
}
</style>
