node( 'buildvm-devops' ) {
	input 'Are you certain you want to perform an upgrade on the dev-preview-int test cluster?'
	sshagent(['dev-preview-int']) {
    		sh 'ssh -o StrictHostKeyChecking=no opsmedic@use-tower1.ops.rhcloud.com upgrade'
	}
}

