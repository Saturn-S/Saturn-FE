<script lang="ts">
    import * as Card from "$lib/components/ui/card";
    import { Input } from "$lib/components/ui/input/index.js";
    import { Label } from "$lib/components/ui/label/index.js";
    import { Button } from "$lib/components/ui/button/index.js";
</script>
   
<div class="min-w-full min-h-dvh flex justify-center items-center saturnbg">
    <Card.Root class="min-w-[400px] max-w-[500px] min-h-[400px] max-h-[500px]">
        <Card.Header>
          <Card.Title tag="h3">Saturn🪐 | Auth</Card.Title>
          <Card.Description class="text-center">Expect the unexpected.</Card.Description>
        </Card.Header>
        <Card.Content class="p-4">
            <div class="flex w-full max-w-sm flex-col gap-1.5 gap-x-2">
                <Label for="username">Username</Label>
                <Input type="username" id="username" placeholder="Username" />
              </div>
              <div class="flex w-full max-w-sm mt-4 flex-col gap-1.5 gap-x-2">
                <Label for="password">Password</Label>
                <Input type="password" id="password" placeholder="Password" />
              </div>
              <div class="flex flex-col items-center mt-2 justify-center">
                <p>Press <a class="hover:cursor-pointer hover:underline text-primary">here</a> to buy a subscription.</p>
                <Button class="mt-4">Login</Button>
              </div>
        </Card.Content>
      </Card.Root>
</div>