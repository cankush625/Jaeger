First install dependencies:  
`kubectl apply -k dependencies`

After that install the Jaeger operator:  
`kubectl apply -k jaeger_operator`

Finally, install Jaeger instance:  
`kubectl apply -k jaeger_instance`
